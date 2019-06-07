<template>
  <v-container grid-list-md>
    <v-flex md12>
      <h1
        class="display-1 mb-0 font-weight-medium black--text"
      >Mejores productos naturales para el cuidado del cabello</h1>
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
      <h1
        class="mb-0 font-weight-medium black--text"
      >El limón y el aceite de oliva para un cuero cabelludo irritable y con caspa</h1>
      <p
        class="headline grey--text text--darken-1 font-weight-light"
      >Para luchar contra la caspa y un cuero cabelludo irritado provocado por una mala alimentación, estrés y el clima entre otros factores, prueba a aplicar una mezcla de jugo de limón y aceite de oliva en el cabello. La acidez en el jugo de limón ayuda a eliminar la caspa del cuero cabelludo y otras cosas como escamas piel seca mientras que el aceite de oliva ayuda a hidratar la piel.</p>
      <h1 class="mb-0 font-weight-medium black--text">Aloe Vera</h1>
      <p
        class="headline grey--text text--darken-1 font-weight-light"
      >El aloe vera es útil para ayudar al crecimiento del cabello, ya que contiene una enzima que estimula los folículos pilosos. Al mismo tiempo, detiene la caída y trata diversos problemas del cuero cabelludo. Podemos utilizarlo mezclando gel de aloe vera con el shampoo o acondicionador, o masajearlo directamente en el cuero cabelludo antes de lavarlo, manteniéndolo en el cabello al menos dos horas. Los efectos se empezarán a notar al mes de uso.</p>
      <h1 class="mb-0 font-weight-medium black--text">Aceite de ricino</h1>
      <p
        class="headline grey--text text--darken-1 font-weight-light"
      >El aceite de castor o ricino no solo es un aceite vegetal humectante, sino que también es un antifúngico. Utilizando este aceite nos aseguraremos de que nuestro cabello está limpio y preparado para crecer mejor.</p>
    </v-flex>
    <div align="center">
      <v-flex md6>
        <v-img
          src="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/productos-naturales-para-el-cabello.jpg?alt=media&token=e9b571c9-16cc-47fa-9392-5ae6b6ac6a24"
          img-blog
        />
      </v-flex>
    </div>
  </v-container>
</template>

<script>
export default {
  head: {
    title: 'Natued - Jarabe Natural',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content:
          'Jarabe natural a base de miel de abeja y kión previene el asma'
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
