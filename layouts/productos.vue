<template>
  <v-app class="white">
    <v-toolbar class="elevation-0 blue" extension-height="250">
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
      <!-- <template v-slot:extension>
        <v-flex md12>
          <div align="center">
            <h1 class="display-1 white--text">Productos</h1>
            <h3
              class="headline grey--text text--lighten-4"
            >Encuentra una gran variedad de productos para el cuidado de tu cuerpo</h3>
          </div>
        </v-flex>
      </template>-->
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
