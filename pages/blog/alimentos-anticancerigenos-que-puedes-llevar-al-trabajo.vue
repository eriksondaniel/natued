<template>
  <v-container grid-list-md>
    <v-flex md12>
      <h1
        class="display-1 mb-0 font-weight-medium black--text"
      >Lista de 10 alimentos anticancerigenos que puedes llevar al trabajo</h1>
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
      >Lista de 10 alimentos anticancerigenos que puedes llevar al trabajo:</p>
      <p class="headline grey--text text--darken-1 font-weight-light">1- Algas marinas</p>
      <p class="headline grey--text text--darken-1 font-weight-light">2- Setas</p>
      <p class="headline grey--text text--darken-1 font-weight-light">3- Frutos secos y semillas</p>
      <p class="headline grey--text text--darken-1 font-weight-light">4- Verduras tipo col</p>
      <p class="headline grey--text text--darken-1 font-weight-light">5- Probióticos (yogur y miso)</p>
      <p class="headline grey--text text--darken-1 font-weight-light">6- Te verde</p>
      <p class="headline grey--text text--darken-1 font-weight-light">8- Cítricos</p>
      <p class="headline grey--text text--darken-1 font-weight-light">9- Cúrcuma</p>
      <p class="headline grey--text text--darken-1 font-weight-light">10- Ajo</p>

      <p
        class="headline grey--text text--darken-1 font-weight-light"
      >Tomar alimentos anticancerígenos como las algas, setas, frutos secos o cítricos puede ayudar a prevenir el cáncer, una enfermedad que es acusada en gran medida por el estilo de vida.</p>
      <p
        class="headline grey--text text--darken-1 font-weight-light"
      >Más allá de una predisposición genética para el desarrollo de tumores malignos, hoy en día la ciencia nos ha abierto los ojos sobre el impacto que tiene el estilo de vida que tenemos</p>
    </v-flex>
    <div align="center">
      <v-flex md6>
        <v-img
          src="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/anticancerigenos.png?alt=media&token=bfcd0134-54e1-4b85-9d9b-7b6ea6dd9599"
          img-blog
        />
      </v-flex>
    </div>
  </v-container>
</template>

<script>
export default {
  head: {
    title: 'Blog - Alimentos Anticancerigenos',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content:
          'Lista de 10 alimentos anticancerigenos que puedes llevar al trabajo'
      }
    ]
  },
  data: () => ({
    autor: 'Dra. Ilche Park',
    date: 'May 4, 2019 - 1 min'
  })
}
</script>

<style>
.img-blog {
  width: 50%;
  height: auto;
}
</style>
