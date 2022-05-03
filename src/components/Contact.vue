<template>
  <section id="Contact">
    <v-container id="sectionContainer" class="indigo accent-3 #3D5AFE">
      <form id="contactForm"
        name="contact"
        method="post"
        v-on:submit.prevent="handleSubmit"
        action="/success/"
        data-netlify="true"
        data-netlify-honeypot="bot-field"
      >
        <input type="hidden" name="form-name" value="contact" />
        <p hidden>
          <label> Don’t fill this out: <input name="bot-field" /> </label>
        </p>
        <div class="sender-info">
          <div>
            
            <input  id="nameEntry" type="text" name="name" placeholder="Full Name" v-model="formData.name" />
          </div>
          <div>

            <input id="emailEntry" type="email" name="email" placeholder="Email" v-model="formData.email" />
          </div>
        </div>

        <div class="message-wrapper">
          <textarea id="messageEntry" name="message" placeholder="Message" v-model="formData.message"></textarea>
        </div>

        <button type="submit">Submit form</button>
      </form>
    </v-container>
  </section>
</template>




<script>
export default {
  metaInfo: {
    title: "Contact",
  },
  data() {
    return {
      formData: {},
    };
  },
  methods: {
    encode(data) {
      return Object.keys(data)
        .map(
          (key) => encodeURIComponent(key) + "=" + encodeURIComponent(data[key])
        )
        .join("&");
    },
    handleSubmit(e) {
      fetch("/", {
        method: "POST",
        headers: { "Content-Type": "application/x-www-form-urlencoded" },
        body: this.encode({
          "form-name": e.target.getAttribute("name"),
          ...this.formData,
        }),
      })
        .then(() => window.location.reload())
        .catch((error) => alert(error));
    },
  },
};
</script>

<style >

#Contact{
  margin-left: 450px;
}



#sectionContainer {
    max-width: 3560px;
}

#contactForm{
  margin-left: 400px;
}

input{
  outline: 3px;
}

#nameEntry{
  min-width: 500px;
}

#emailEntry{
  min-width: 500px;
}

#messageEntry{
  min-width: 500px;
}

button, input, select, textarea {
    background-color: white;
    border-style:solid;
    border-color:black ;
    margin-left: 10px;
    margin-bottom: 10px;
}

</style>