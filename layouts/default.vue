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
        <v-btn
          flat
          @click="toMain"
        >
          Inicio
        </v-btn>
        <v-btn
          flat
          @click="toBlog"
        >
          Blog
        </v-btn>
        <v-btn flat>¿Cómo funciona?</v-btn>
        <v-btn flat>Productos</v-btn>
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
  },
  methods: {
    toMain() {
      this.$router.push('/')
    },
    toBlog() {
      this.$router.push('/blog')
    }
  }
}
</script>
