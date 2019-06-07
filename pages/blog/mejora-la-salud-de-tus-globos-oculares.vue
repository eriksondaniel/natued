<template>
  <v-container grid-list-md>
    <v-flex md12>
      <h1
        class="display-1 mb-0 font-weight-medium black--text"
      >!Mejora la salud de tus globos oculares!</h1>
    </v-flex>
    <v-flex md12 py-3>
      <v-list-tile avatar>
        <v-list-tile-avatar>
          <img src="https://cdn.vuetifyjs.com/images/lists/2.jpg">
        </v-list-tile-avatar>

        <v-list-tile-content>
          <v-list-tile-title v-html="autor"></v-list-tile-title>
          <v-list-tile-sub-title class="grey--text text--darken-1" v-html="date"></v-list-tile-sub-title>
        </v-list-tile-content>
      </v-list-tile>
    </v-flex>
    <v-flex md12 pa-2>
      <p
        class="headline grey--text text--darken-1 font-weight-light"
      >Hoy no hablaremos de muchos productos que te ayudarán a tu salud sino uno en específico.</p>
      <p
        class="headline grey--text text--darken-1 font-weight-light"
      >Siendo el betacaroteno un gran motivador de la vitamina A, esencial para la salud ocular (la falta de vitamina A puede provocar ceguera y otros problemas en los ojos como la xeroftalmia), y estando tan presente en las zanahorias, su consumo puede mejorar la salud de los globos oculares, lo cual no significa que mejore tu visión.</p>
    </v-flex>
    <div align="center">
      <v-flex md6>
        <v-img
          src="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/globs-oculares.png?alt=media&token=470d27fe-5c89-4023-9917-5715e98b1563"
          img-blog
        />
      </v-flex>
    </div>
  </v-container>
</template>

<script>
export default {
  head: {
    title: 'Natued - Globos Oculares',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: '!Mejora la salud de tus globos oculares!'
      }
    ]
  },
  data: () => ({
    autor: 'Dra. Ilche Park',
    date: 'May 11, 2019 - 1 min'
  })
}
</script>

<style>
</style>
