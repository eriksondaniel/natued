<template>
  <v-container grid-list-md>
    <v-flex md12>
      <h1 class="display-1 mb-0 font-weight-medium black--text">¿Qué es la medicina natural?</h1>
    </v-flex>
    <v-flex
      md12
      py-3
    >
      <v-list-tile avatar>
        <v-list-tile-avatar>
          <img src="https://cdn.vuetifyjs.com/images/lists/2.jpg">
        </v-list-tile-avatar>

        <v-list-tile-content>
          <v-list-tile-title v-html="autor"></v-list-tile-title>
          <v-list-tile-sub-title
            class="grey--text text--darken-1"
            v-html="date"
          ></v-list-tile-sub-title>
        </v-list-tile-content>
      </v-list-tile>
    </v-flex>
    <v-flex
      md12
      pa-2
    >
      <p class="headline grey--text text--darken-1 font-weight-light">Medicina alternativa es toda práctica que afirma tener los efectos sanadores de la medicina pero que no está apoyada por pruebas obtenidas mediante el método científico, por lo que su efectividad no ha sido probada científicamente más allá del efecto placebo. Consiste en un amplio rango de prácticas, productos y «terapias».En esta denominación se incluyen prácticas pseudomédicas nuevas y tradicionales como homeopatía, naturopatía, quiropraxia, curación energética, ozonoterapia, radiestesia, acupuntura, medicina tradicional china, medicina ayurvédica, curación divina, junto a otros tratamientos que no son parte de la medicina científica</p>
    </v-flex>
    <div align="center">
      <v-flex md6>
        <v-img
          src="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/medicina-natural.jpg?alt=media&token=aef53a84-6e2c-4539-bc63-88ed12ccdeca"
          img-blog
        />
      </v-flex>
    </div>
  </v-container>
</template>

<script>
export default {
  head: {
    title: 'Blog - Medicina Natural',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: '¿Qué es la medicina natural?'
      }
    ]
  },

  data: () => ({
    autor: 'Luis Guzman',
    date: 'Mar 25, 2019 - 1 min'
  })
}
</script>

<style>
</style>
