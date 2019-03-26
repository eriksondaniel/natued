<template>
  <v-app class="white">
    <v-toolbar
      app
      class="white elevation-1"
    >
      <v-spacer />
      <v-toolbar-title>
        <h1 class="title font-weight-regular accent--text">NATUED</h1>
      </v-toolbar-title>
      <v-spacer />
      <v-spacer />
      <v-spacer />
      <v-toolbar-items>
        <v-btn flat>Link One</v-btn>
        <v-btn flat>Link Two</v-btn>
        <v-btn flat>Link Three</v-btn>
      </v-toolbar-items>
      <v-spacer />
    </v-toolbar>
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>

    <v-footer app>
      <span>&copy; 2019</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      title: 'Vuetify.js'
    }
  }
}
</script>
