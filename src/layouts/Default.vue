<template>
  <v-app>
    <v-card height="100%" width="256" class="mx-auto">
      <v-navigation-drawer class="indigo accent-3 #3D5AFE" dark permanent app>
        <v-container id="header-info">
        <v-avatar>
        <v-img src="https://raw.githubusercontent.com/mrusse54/my-gridsome-site/main/src/images/me.jpg?token=GHSAT0AAAAAABSU3CGD6WWXFTXOMU5SQUXUYTQQBGA"> </v-img>
            
          </v-avatar>
        <v-list-item>
          <v-list-item-content>
            <v-list-item-title class="text-h6">
              Mitchell Russell
            </v-list-item-title>
            <v-list-item-subtitle>software Engineer</v-list-item-subtitle>
          </v-list-item-content>
        </v-list-item>
        </v-container>

        <v-divider class="indigo darken-4"></v-divider>

        <v-list dense nav>
          <v-list-item v-for="item in items" :key="item.title" link :to="`#${item.title}`">
            <v-list-item-icon>
              <v-icon>{{ item.icon }}</v-icon>
            </v-list-item-icon>
            <v-list-item-content>
              <v-list-item-title>{{ item.title }}</v-list-item-title>
            </v-list-item-content>
          </v-list-item>
        </v-list>
      </v-navigation-drawer>
    </v-card>
    <v-main>
      <slot />
    </v-main>
  </v-app>

</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<script>
export default {
  data() {
    return {
      items: [
        { title: "About", icon: "mdi-account" },
        { title: "Courses", icon: "mdi-school" },
        { title: "Projects", icon: "mdi-github"},
        { title: "Resume", icon: "mdi-briefcase"},
        { title: "Contact", icon: "mdi-linkedin"},
      ],
      right: null,
    };
  },
};
</script>

<style>
body {
  font-family: -apple-system, system-ui, BlinkMacSystemFont, "Segoe UI", Roboto,
    "Helvetica Neue", Arial, sans-serif;
  margin-left: -778px;
  padding: 0;
  line-height: 1.5;
}

.layout {
  max-width: 760px;
  margin: 0 auto;
  padding-left: 20px;
  padding-right: 20px;
}

.nav__link {
  margin-left: 20px;
}

.v-application--wrap {
  flex-direction: row;
}

.v-container {
  padding-left: 100px;
}

.theme--light.v-application {
  background: white;
  color: black;
}
.v-main__wrap {
  margin-top: 10px;
  margin-left: 20px;
}

#header-info{
 text-align: center;
}



</style>
