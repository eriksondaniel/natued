<template>
  <v-container grid-list-md>
    <v-flex md12>
      <h1
        class="display-1 mb-0 font-weight-medium black--text"
      >La zanahoria y sus propiedades medicinales</h1>
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
      >Te damos la receta del mejor extracto de zanahoria que te protegen de las enfermedades en el invierno.</p>
      <p>
        <iframe
          width="640"
          height="400"
          src="http://www.powtoon.com/embed/cDbwVHrMv91/"
          frameborder="0"
        />
      </p>
    </v-flex>
    <!-- <div align="center">
      <v-flex md6>
        <v-img
          src="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/zanahorias.jpg?alt=media&token=f0cdba04-6909-4360-bf6e-9b597cd6b056"
          img-blog
        />
      </v-flex>
    </div> -->
  </v-container>
</template>

<script>
export default {
  head: {
    title: 'Natued - Propiedades Salvia',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: '6 propiedades curativas de la salvia'
      }
    ]
  },
  data: () => ({
    autor: 'Dra. Ilche Park',
    date: 'Jun 08, 2019 - 1 min'
  })
}
</script>

<style>
</style>
