<template>
  <section id="Resume">
    <v-container id="resumeContainer" >
      <v-row id="resumeRow">
        <v-card elevation="0">
          <v-divider class="indigo accent-3"></v-divider>
          <v-toolbar flat class="white" dark>
            <v-toolbar-title
              ><v-icon left color="black"> mdi-school </v-icon>
              EDUCATION</v-toolbar-title
            >
          </v-toolbar>
          <v-divider id="resumeDiv" class="indigo accent-3"></v-divider>
          <v-card flat>
            <v-card-text id="courseText">
              <p>
                University of North Carolina Charlotte (UNCC), Charlotte, NC
                December 2022
              </p>

              <p>
                Bachelor of Science in Computer Science | Concentration:
                Software Engineering GPA: 3.89
              </p>
              <p>Honors: Chancellor’s List: Fall 2020</p>

              <p class="mb-0"></p>
            </v-card-text>
          </v-card>
        </v-card>
      </v-row>

      <v-row id="resumeRow">
        <v-card elevation="0">
          <v-divider class="indigo accent-3"></v-divider>
          <v-toolbar flat class="white" dark>
            <v-toolbar-title
              ><v-icon left color="black"> mdi-laptop </v-icon>Thechnical
              Skills</v-toolbar-title
            >
          </v-toolbar>
          <v-divider id="resumeDiv" class="indigo accent-3"></v-divider>
          <v-card flat>
            <v-card-text id="courseText">
              <p>languages:</p>

              <p>JavaScript, C++, HTML</p>
              <p class="mb-0"></p>
            </v-card-text>
          </v-card>
        </v-card>
      </v-row>

      <v-row id="resumeRow">
        <v-card elevation="0">
          <v-divider class="indigo accent-3"></v-divider>
          <v-toolbar flat class="white" dark>
            <v-toolbar-title
              ><v-icon left color="black"> mdi-tie </v-icon> Employment
              History</v-toolbar-title
            >
          </v-toolbar>
          <v-divider id="resumeDiv" class="indigo accent-3"></v-divider>
          <v-card flat>
            <v-card-text id="courseText">
             

              <p>
                University of North Carolina Charlotte, Charlotte, NC Jan 2021 –
                May 2022
              </p>
              <p>Teachers Assistant</p>
              <p>• Facilitated learning in the classroom</p>
              <p>•Graded assignments and held office hours for students</p>
              <p>Macon Mayhem, Macon, GA 2017 – 2018 (Seasonal)</p>
              <p>Activity Director</p>
              <p>
                • Responsible for assisting in the execution of in-game elements
                of a Macon Mayhem hockey games.
              </p>
              <p>
                • Interacted with fans to ensure that their time at a Macon
                Mayhem hockey game was fun, memorable, and safe
              </p>
              <p>Arden Companies, Sanford, NC 2016 – 2017 (Seasonal)</p>
              <p>Costumer Sales Associate</p>
              <p>• Responsible for sales and customer service</p>
              <p>
                • Sales included outdoor furniture pillows, cushions, and
                umbrellas
              </p>
              <p>
                • Customer service included helping customers find products,
                match patterns, checkout, and returns
              </p>
              

              <p class="mb-0"></p>
            </v-card-text>
          </v-card>
        </v-card>
      </v-row>




    </v-container>
  </section>
</template>

<script>
export default {
  metaInfo: {
    title: "Resume",
  },
};
</script>

<style >

#Resume{
  margin-left: 700px;
}

#resumeContainer .v-toolbar-title {
  color: "indigo accent-3";
  margin-right: 100px;
}

#resumeContainer .v-tabs-title {
  margin-right: 100px;
}

#resumeContainer .v-tabs {
  flex: 1 1 auto;
  width: 100%;
  margin-top: -10px;
}

#resumeContainer .v-toolbar__content,
.v-toolbar__extension {
  color: black;
  align-items: center;
  display: flex;
  position: relative;
  z-index: 0;
  /* margin-top: -5px; */
  margin-left: -12px;
}

#cardTitle .v-toolbar__content {
  margin-bottom: -10px;
}

#courseText {
  color: black;
}
</style>
