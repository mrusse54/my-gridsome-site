<template>
  <section id="About">
    <v-container>
      <v-row id="introRow"
        ><v-col id="portrait"
          ><v-img
            alt="Mitchell Russell"
            src="https://raw.githubusercontent.com/mrusse54/my-gridsome-site/main/src/images/me.jpg?token=GHSAT0AAAAAABSU3CGD6WWXFTXOMU5SQUXUYTQQBGA"
            width="400"
          ></v-img
        ></v-col>
        <v-col>
          <h2 id="intro">
            Hello my name is Mitchell Russell. I am a Computer Science student
            at University of North Carolina at Charlotte majoring in Software
            Engineering. I am Currently a senior with a graduation date of Fall
            2022. I am exicted to begin a carreer in the Software Engineering
            feild. I am looking for a job in Software Engineering feild. I have
            experince in Javascript, C++, HTML, and Vue.js
          </h2>
        </v-col>
      </v-row>
    </v-container>

    <v-container class="indigo accent-3 #3D5AFE">
      <v-timeline>
        <v-timeline-item
          v-for="(year, i) in years"
          :key="i"
          :color="year.color"
          small
        >
          <template v-slot:opposite>
            <span
              :class="`headline font-weight-bold ${year.colorText}--text`"
              v-text="year.year"
            ></span>
          </template>
          <div class="py-4" color="white">
            <h2
              :class="`headline font-weight-light mb-4 ${year.colorText}--text`"
              v-text="year.school"
            ></h2>
            <div
              :class="` mb-0 ${year.colorText}--text`"
              v-text="year.bio"
            ></div>
          </div>
        </v-timeline-item>
      </v-timeline>
    </v-container>
  </section>
</template>

<script>
export default {
  metaInfo: {
    title: "About",
  },
  data: () => ({
    years: [
      {
        color: "black",
        colorText: "white",
        year: "2018",
        school: "Graduated Highschool",
        bio: "Graduated from Russell Boys Academy",
      },
      {
        color: "black",
        colorText: "white",
        year: "2019",
        school: "Central Piedmont Community College",
        bio: "Attended CPCC for general credits",
      },
      {
        color: "black",
        colorText: "white",
        year: "2020",
        school: "Accepted into University of North Carolina",
        bio: "Accepted into UNCC for undergraduate studies",
      },
      {
        color: "black",
        colorText: "white",
        year: "2021",
        school: "University of North Carolina",
        bio: "Declared major in Computer Science with a concentration in Software engineering",
      },
      {
        color: "black",
        colorText: "white",
        year: "2022",
        school: "University of North Carolina Graduation",
        bio: "Fall 2022 is my intended graduation date",
      },
    ],
  }),
};
</script>

<style >
#portrait {
  margin-right: -700px;
}

#About {
  margin-left: 525px;
}

#intro {
  max-width: 600px;
  margin-left: 200px;
}

#introRow {
  margin-left: 400px;
}
</style>
