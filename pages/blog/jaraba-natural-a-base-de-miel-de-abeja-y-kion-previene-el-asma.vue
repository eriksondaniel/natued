<template>
  <v-container grid-list-md>
    <v-flex md12>
      <h1
        class="display-1 mb-0 font-weight-medium black--text"
      >Jarabe natural a base de miel de abeja y kión previene el asma</h1>
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
      >Las personas asmáticas, en especial los niños, son sensibles a la llegada del otoño, época en que se incrementan sus visitas a los hospitales. Por ello, un jarabe natural -elaborado en base a miel de abeja, ajos, cebolla y kión o jenjibre- es un aliado en la prevención de esta enfermedad, sostuvieron especialistas de EsSalud.</p>
      <p
        class="headline grey--text text--darken-1 font-weight-light"
      >Martha Villar López, directora de Medicina Complementaria del Seguro Social de Salud (EsSalud), dijo que el ajo y la cebolla tienen poderosos efectos antioxidantes y broncodilatadores que ayudan a prevenir cuadros de asma.</p>
      <p
        class="headline grey--text text--darken-1 font-weight-light"
      >“Un jarabe bronquial que se elabora con la mezcla de miel de abeja, cebolla, ajo y kión, el cual puede ser consumido entre 1 a 3 cucharadas diarias, ayuda a prevenir el asma”, recomendó la especialista.</p>
      <p
        class="headline grey--text text--darken-1 font-weight-light"
      >Precisó que gracias a su contenido de aceites esenciales, el ajo es un relajante de la musculatura lisa y además es un expectorante. Debido a su compuesto de aliina tiene un efecto antibiótico y antimicótico. La cebolla por su parte tiene quercetina, un potente compuesto antioxidante, que le da acción antialérgica a esta hortaliza.</p>
    </v-flex>
    <div align="center">
      <v-flex md6>
        <v-img
          src="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/jarabe_de_miel_ajo_kion.jpg?alt=media&token=43fbdded-3f0e-44c7-8d29-b46f67b0435a"
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
