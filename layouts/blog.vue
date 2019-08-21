<template>
  <v-app class="white">
    <v-toolbar flat class="success" extension-height="250">
      <v-spacer/>
      <nuxt-link to="/">
        <img src="~/assets/logo-2.svg" alt="natued-logo" width="40px" height="40x">
      </nuxt-link>
      <v-spacer/>
      <v-spacer/>
      <v-spacer/>
      <v-toolbar-items>
        <v-btn flat @click="toBlog" class="white--text">Blog</v-btn>
      </v-toolbar-items>
      <v-spacer/>
      <template v-slot:extension>
        <v-flex md12 class="text-xs-center">
          <h1 class="display-1 white--text">NatuBlog</h1>
          <br>
          <h3
            class="headline grey--text text--lighten-4"
          >Encuentra las mejores publicaciones de medicina natural</h3>
        </v-flex>
      </template>
    </v-toolbar>
    <v-content>
      <nuxt/>
    </v-content>
    <v-footer class="white mb-4">
      <v-layout row wrap>
        <v-container>
          <v-divider dropzone/>
          <v-layout row wrap class="white mt-2">
            <span>Copyright {{ new Date().getFullYear() }} &copy;brainti. All rights reserved.</span>
            <v-spacer/>
            <span>&copy;Terms of Use & Privacy Policy</span>
          </v-layout>
        </v-container>
      </v-layout>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  data() {
    return {
      extended: true
    }
  },
  methods: {
    toMain() {
      this.$router.push('/')
    },
    toBlog() {
      this.$router.push('/blog')
    },
    toggleExtension() {
      this.extended = !this.extended
    }
  }
}
</script>

<style>
</style>
