<template>
<div id="app">
  <v-app id="inspire">
    <v-app id="inspire">
      <v-navigation-drawer
        v-model="drawer"
        app
      >
        <v-list dense>
          <v-list-item link>
            <v-list-item-action>
              <v-icon>mdi-home</v-icon>
            </v-list-item-action>
            <v-list-item-content>
              <v-list-item-title>Home</v-list-item-title>
            </v-list-item-content>
          </v-list-item>
          <v-list-item link>
            <v-list-item-action>
              <v-icon>mdi-email</v-icon>
            </v-list-item-action>
            <v-list-item-content>
              <v-list-item-title>Contact</v-list-item-title>
            </v-list-item-content>
          </v-list-item>
        </v-list>
      </v-navigation-drawer>
  
      <v-app-bar
        app
        color="blue darken-1"
        dark
      >
        <v-app-bar-nav-icon @click.stop="drawer = !drawer"></v-app-bar-nav-icon>
        <v-toolbar-title>Application</v-toolbar-title>
      </v-app-bar>
  
      <v-main>
        <v-container
          fluid
        >
          <v-row
            align="center"
            justify="center"
          >
            <v-col class="text-left">
                <Index left></Index>
            </v-col>
          </v-row>
        </v-container>
      </v-main>
      <v-footer
        color="blue darken-1"
        app
      >
        <span class="white--text">&copy; 清澜山学生网 2021</span>
      </v-footer>
    </v-app>
  </v-app>
</div></template>

<script>
import Index from "./components/Index.vue";
export default {
  name: 'App',

  components: {

    Index,
  },

  data: () => ({
    //
  }),
};
</script>
