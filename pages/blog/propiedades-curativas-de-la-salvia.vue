<template>
  <v-container grid-list-md>
    <v-flex md12>
      <h1 class="display-1 mb-0 font-weight-medium black--text">6 propiedades curativas de la salvia</h1>
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
      >Se conoce desde la antigüedad como una planta mediterránea, útil para muchas situaciones debido a la gran cantidad de propiedades curativas que posee..</p>
      <p
        class="headline grey--text text--darken-1 font-weight-light"
      >1. Aliviar los dolores menstruales</p>
      <p
        class="headline grey--text text--darken-1 font-weight-light"
      >2. Disminuye el dolor en enfermedades reumáticas</p>
      <p
        class="headline grey--text text--darken-1 font-weight-light"
      >3. Mejora la digestión y la acidez.</p>
      <p class="headline grey--text text--darken-1 font-weight-light">4. Planta antiséptica</p>
      <p class="headline grey--text text--darken-1 font-weight-light">5. Reduce la glucemia</p>
      <p class="headline grey--text text--darken-1 font-weight-light">6. Mejora la memoria</p>
    </v-flex>
    <div align="center">
      <v-flex md6>
        <v-img
          src="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/sabia.png?alt=media&token=07ae1040-89ce-496a-97c2-1cc9a194da60"
          img-blog
        />
      </v-flex>
    </div>
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
        content:
          '6 propiedades curativas de la salvia'
      }
    ]
  },
  data: () => ({
    autor: 'Dra. Ilche Park',
    date: 'May 18, 2019 - 1 min'
  })
}
</script>

<style>
</style>
