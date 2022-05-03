<template>
  <section id="Courses">
    <v-container>
      <v-row id="courseRowTop">
        <v-col>
          <v-card id="bigCard">
            <v-toolbar flat class="indigo accent-3" dark>
              <v-toolbar-title
                >ITIS 3135 - Web-Based Application Design and
                Development</v-toolbar-title
              >
            </v-toolbar>
            <v-tabs vertical>
              <v-tab>
                <v-icon left> mdi-robot </v-icon>
                Description
              </v-tab>
              <v-tab>
                <v-icon left> mdi-map </v-icon>
                Outline
              </v-tab>
              <v-tab>
                <v-icon left> mdi-pencil </v-icon>
                Assignments
              </v-tab>

              <v-tab-item>
                <v-card flat>
                  <v-card-text id="courseText">
                    <p class="mb-0">
                      HTML, CSS, the Document Object Model (DOM), event-driven
                      programming, client side scripting, and web security
                      considerations.
                    </p>
                  </v-card-text>
                </v-card>
              </v-tab-item>
              <v-tab-item>
                <v-card flat>
                  <v-card-text id="courseText">
                    <p>
                      There are five graded assignments to complete over the
                      semester consisting of Three are programming assignments
                      and two are exams.
                    </p>
                    <p>Programming assignments:</p>
                    <p>
                      Eight Queens: Hill-Climbing with random restarts algorithm
                    </p>
                    <p>A* Search: A* with Manhattan method</p>
                    <p>Bomber Belts: AI game</p>

                    <p>Exams: Covers content related to projects</p>

                    <p class="mb-0"></p>
                  </v-card-text>
                </v-card>
              </v-tab-item>
              <v-tab-item>
                <v-card flat>
                  <v-card-text id="courseText">
                    <p>Assignments can be seen on the projects page.</p>
                    <p>
                      The links to the github for Eight Queens and A* Search can
                      be found on the projects page.
                    </p>

                    <p class="mb-0">
                      <v-btn
                        class="indigo accent-3"
                        block
                        href="https://github.com/mrusse54?tab=repositories"
                      >
                        Repositorie Link
                      </v-btn>
                    </p>
                  </v-card-text>
                </v-card>
              </v-tab-item>
            </v-tabs>
          </v-card>
        </v-col>

        <v-col>
          <v-card id="bigCard">
            <v-toolbar flat class="indigo accent-3" dark>
              <v-toolbar-title
                >ITIS 3300 - Software Requirements and Project
                Management</v-toolbar-title
              >
            </v-toolbar>
            <v-tabs vertical>
              <v-tab>
                <v-icon left> mdi-tie </v-icon>
                Description
              </v-tab>
              <v-tab>
                <v-icon left> mdi-map </v-icon>
                Outline
              </v-tab>
              <v-tab>
                <v-icon left> mdi-pencil </v-icon>
                Assignments
              </v-tab>

              <v-tab-item>
                <v-card flat>
                  <v-card-text id="courseText">
                    <p class="mb-0">
                      Introduction to requirement engineering and project
                      management methodologies. Topics include: requirements
                      elicitation, specification, and validation; structural,
                      informational, behavioral, security, privacy, and computer
                      user interface requirements; scenario analysis;
                      application of object-oriented methodologies in
                      requirements gathering; spiral development model; risk
                      management models; software engineering maturity model;
                      project planning and milestones; cost estimation; team
                      organizations and behavior. Case studies will be used.
                    </p>
                  </v-card-text>
                </v-card>
              </v-tab-item>
              <v-tab-item>
                <v-card flat>
                  <v-card-text id="courseText">
                    <p>There are three weekly assignments and one project:</p>

                    <p>
                      Quizes: On weekly reading of Information Technology
                      Project Management
                    </p>

                    <p>
                      Agile Stories: Creating user stories from the chapter read
                      and putting them into an Agile methodoly
                    </p>

                    <p>
                      Peer Reviews: Reading other students blogs and giving back
                      feedback
                    </p>

                    <p>
                      Group Discussions: Document created by the team containing
                      user stories, sprint retrospectives and acceptance
                      criteria
                    </p>

                    <p class="mb-0">
                      Project: Website that the blogs are posted
                    </p>
                  </v-card-text>
                </v-card>
              </v-tab-item>
              <v-tab-item>
                <v-card flat>
                  <v-card-text id="courseText">
                    <p>
                      The group project is a blog that contains all the articles
                      that have been written by the team.
                    </p>
                    <p>A link to the website can be found bellow.</p>

                    <p class="mb-0">
                      <v-btn
                        block
                        href="https://mrusse54.wixsite.com/agile"
                        class="indigo accent-3"
                      >
                        Blog link
                      </v-btn>
                    </p>
                  </v-card-text>
                </v-card>
              </v-tab-item>
            </v-tabs>
          </v-card>
        </v-col>
      </v-row>

      <v-row id="courseRowBottom">
        <v-col>
          <v-card id="bigCard">
            <v-toolbar flat class="indigo accent-3" dark>
              <v-toolbar-title
                >ITIS 3310 - Software Architecture and Design</v-toolbar-title
              >
            </v-toolbar>
            <v-tabs vertical>
              <v-tab>
                <v-icon left> mdi-monitor </v-icon>
                Description
              </v-tab>
              <v-tab>
                <v-icon left> mdi-map </v-icon>
                Outline
              </v-tab>
              <v-tab>
                <v-icon left> mdi-pencil </v-icon>
                Assignments
              </v-tab>

              <v-tab-item>
                <v-card flat>
                  <v-card-text id="courseText">
                    <p class="mb-0">
                      Introduction to software design with emphasis on
                      architectural design and design patterns. Models of
                      software architecture. Architecture styles and patterns,
                      including explicit, event-driven, client-server, and
                      middleware architectures. Decomposition and composition of
                      architectural components and interactions. Use of
                      non-functional requirements for tradeoff analysis.
                      Component based software development, deployment and
                      management. A system design language, such as UML, are
                      introduced and used throughout the course.
                    </p>
                  </v-card-text>
                </v-card>
              </v-tab-item>
              <v-tab-item>
                <v-card flat>
                  <v-card-text id="courseText">
                    <p>
                      There are one weekly group assignment, weekly reading, two
                      projects over the semester, and two test:
                    </p>

                    <p>
                      Group Assignment: Essay questions are given on weekly
                      reading
                    </p>

                    <p>
                      weekly Reading: Software Engineering: A Practitioner's
                      Approach and Debugging Teams: Better Productivity through
                      Collaboration
                    </p>

                    <p>
                      Projects: Group project on group created product and
                      research paper on students choice
                    </p>

                    <p class="mb-0">Tests: Mid term and final exam</p>
                  </v-card-text>
                </v-card>
              </v-tab-item>
              <v-tab-item>
                <v-card flat>
                  <v-card-text id="courseText">
                    <p>
                      My research paper is on automatic speech recognition
                      (ASR).
                    </p>
                    <p>A link to the paper can be found bellow.</p>

                    <p class="mb-0">
                      <v-btn
                        block
                        href="https://docs.google.com/document/d/14Kgk0lIokMkcTNLpkVwTMLpD9Kvxo7EsWQrR0FBZoWg/edit?usp=sharing"
                        class="indigo accent-3"
                      >
                        Research Paper Link
                      </v-btn>
                    </p>
                  </v-card-text>
                </v-card>
              </v-tab-item>
            </v-tabs>
          </v-card>
        </v-col>

        <v-col>
          <v-card id="bigCard">
            <v-toolbar class="indigo accent-3" dark>
              <v-toolbar-title
                >ITIS 4440 - Interactive Systems Design and Implementation
              </v-toolbar-title>
            </v-toolbar>
            <v-tabs vertical>
              <v-tab>
                <v-icon left> mdi-cloud </v-icon>
                Description
              </v-tab>
              <v-tab>
                <v-icon left> mdi-map </v-icon>
                Outline
              </v-tab>
              <v-tab>
                <v-icon left> mdi-pencil </v-icon>
                Assignments
              </v-tab>

              <v-tab-item>
                <v-card flat>
                  <v-card-text id="courseText">
                    <p class="mb-0">
                      An introduction to the fundamentals of implementing
                      interactive systems, with a focus on human-centered
                      design. Topics include: architecture of interaction
                      applications, event handling, direct vs. indirect GUI
                      programming, 2D graphics programming, layout, design
                      patterns, and design critique. Students learn the
                      fundamental theory of the graphics programming, layout,
                      design patterns, and design critique. Students learn the
                      fundamental theory of the Model-View Controller
                      Architecture and apply it to building a complete
                      standalone application. Outcomes include the creation of a
                      full application with multiple different views that
                      communicate with a single model, as well as experience
                      working with GUI programming and implementing common
                      interaction design patterns such as direct manipulation
                      and drag and drop.
                    </p>
                  </v-card-text>
                </v-card>
              </v-tab-item>
              <v-tab-item>
                <v-card flat>
                  <v-card-text id="courseText">
                    <p>
                      There are weekly assignment, two projects over the
                      semester, and one exam:
                    </p>

                    <p>
                      Weekly Assignments: Various assignments on the topics of
                      System Design, Postman, Vue, and Alexa
                    </p>

                    <p>
                      Individual project: Anything you want to create that uses
                      Vue and API calls
                    </p>

                    <p>
                      Group project: Same as Individual project, but with a
                      group
                    </p>

                    <p class="mb-0">
                      Exam: Mid term that covers material related to postman and
                      weekly assignments
                    </p>
                  </v-card-text>
                </v-card>
              </v-tab-item>
              <v-tab-item>
                <v-card flat>
                  <v-card-text id="courseText">
                    <p>
                      The current website you are on is my individual project
                    </p>
                  </v-card-text>
                </v-card>
              </v-tab-item>
            </v-tabs>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>

<script>
export default {
  metaInfo: {
    title: "Courses",
  },
};
</script>

<style >

#Courses{
  margin-left: 525px;
}


#courseRowBottom {
  margin-top: 30px;
  margin-bottom: 100px;
  min-width: 900px;
  max-width: 900;
  max-height: 400px;
  min-height: 400px;
}

#courseRowTop {
  margin-top: 30px;
  margin-bottom: 30px;
  min-width: 900px;
  max-width: 900;
  max-height: 400px;
  min-height: 400px;
}

#courseText {
  color: black;
}

#bigCard {
  min-width: 868px;
  max-width: 868px;
  max-height: 400px;
  min-height: 400px;
}
</style>
