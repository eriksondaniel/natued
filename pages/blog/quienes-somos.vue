<template>
  <v-container grid-list-md>
    <v-flex md12>
      <h1>Quienes Somos</h1>
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
      <h1 class="mb-0 font-weight-medium black--text">¿Quiénes somos?</h1>
      <p
        class="headline grey--text text--darken-1 font-weight-light"
      >Somos una startup que busca proponer una alternativa al cuidado de la salud, a travez de nuestra aplicación móvil</p>
      <p
        class="headline grey--text text--darken-1 font-weight-light"
      >“Natued” es una plataforma que ofrecerá información detallada de estos medicamentos para facilitar al usuario el encontrar una mayor cantidad de soluciones para mejorar su salud.</p>
    </v-flex>
    <div align="center">
      <v-flex md6>
        <img src="~/assets/logo.svg" alt="natued-logo" width="100px" height="100px">
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
