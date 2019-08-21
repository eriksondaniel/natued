<template>
  <v-app>
    <v-toolbar app flat class="white">
      <v-spacer/>
      <nuxt-link to="/">
        <img src="~/assets/logo.svg" alt="natued-logo" width="40px" height="40x">
      </nuxt-link>
      <v-spacer/>
      <v-spacer/>
      <v-spacer/>
      <v-toolbar-items class="success">
        <v-btn flat class="white--text" @click="toBlog">Blog</v-btn>
      </v-toolbar-items>
      <v-spacer/>
    </v-toolbar>
    <v-content>
      <nuxt/>
    </v-content>
    <v-footer class="white pa-4">
      <v-layout row wrap>
        <v-container>
          <v-divider dropzone/>
          <v-layout row wrap class="mt-2">
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
  methods: {
    toBlog() {
      this.$router.push('/blog')
      this.$ga.event({
        eventCategory: 'blog',
        eventAction: 'action',
        eventLabel: 'label',
        eventValue: 1
      })
    }
  }
}
</script>
