<template>
  <v-layout column>
    <v-container grid-list-md class="white" fluid>
      <v-container>
        <v-layout row wrap align-center justify-center>
          <v-flex xs12 sm6 md4>
            <h2 class="font-weight-regular display-1">Permite</h2>
            <h2 class="font-weight-regular display-1">
              que lo
              <span class="font-weight-bold span-h2">NATURAL</span>
            </h2>
            <h2 class="font-weight-regular display-1">
              sea
              <span class="font-weight-bold span-h2">MEDICINAL</span>
            </h2>
            <br>
            <br>
            <v-btn @click="toApp" depressed color="success white--text">USAR APLICACIÓN</v-btn>
          </v-flex>
          <v-flex md1/>
          <v-flex xs12 sm6 md6>
            <img src="image.png" alt="Natued" class="img-home">
          </v-flex>
        </v-layout>
      </v-container>
    </v-container>
    <!-- https://dribbble.com/andrschk 
                https://cdn.dribbble.com/users/1062785/screenshots/6059370/healthcare-landing_4x.png
                https://cdn.dribbble.com/users/1062785/screenshots/6004265/healthcare-dashboard_4x.png
                https://cdn.dribbble.com/users/1062785/screenshots/5940935/healthcare__4x.png
    -->
    <v-container grid-list-md my-4>
      <v-layout row wrap>
        <v-flex md12 class="text-xs-center">
          <h1 class="font-weight-medium success--text">Vive más con Natued</h1>
          <br>
        </v-flex>
        <CardHowWork
          image="doctor.svg"
          title="Medicos especialistas"
          content="Responden tus preguntas y consultas medicas"
        />
        <CardHowWork
          image="medicine.svg"
          title="Compra productos naturales"
          content="Encuentra los productos de las mejores marcas"
        />
        <CardHowWork
          image="medical-research.svg"
          title="Programa una cita"
          content="Encuentra un médico especialista en medicina natural"
        />
      </v-layout>
    </v-container>
    <v-container grid-list-md class="white" fluid>
      <v-container>
        <v-layout row wrap>
          <v-flex md6>
            <img src="image-2.png" alt class="img-home">
          </v-flex>
          <v-flex md1/>
          <v-flex md5>
            <v-layout column wrap>
              <v-flex xs12 sm12 md12>
                <h1 class="font-weight-medium success--text">¿Cómo funciona?</h1>
                <br>
              </v-flex>
              <CardFunction
                image="one.svg"
                title="Medicos especialistas"
                content="Responden tus preguntas y consultas medicas"
              />
              <CardFunction
                image="two.svg"
                title="Compra productos naturales"
                content="Encuentra los productos de las mejores marcas"
              />
              <CardFunction
                image="three.svg"
                title="Programa una cita"
                content="Encuentra un médico especialista en medicina natural"
              />
            </v-layout>
          </v-flex>
        </v-layout>
      </v-container>
    </v-container>

    <v-container grid-list-md>
      <v-layout row wrap py-4 align-center>
        <v-flex md4>
          <h1 class="font-weight-medium text-sm-center">¿Qué es Natued?</h1>
        </v-flex>
        <v-flex md8>
          <p class="title font-weight-light">
            Natued es una plataforma multicanal de preguntas y respuestas la cual
            permite a sus usuarios formular preguntas relacionadas al campo de la salud anónimamente, las cuales son respondidas gratuitamente por profesionales en el área de la Medicina natural.
          </p>
        </v-flex>
      </v-layout>
    </v-container>
    <v-container grid-list-md fluid class="white">
      <v-container class="text-sm-center">
        <h1 class="font-weight-medium success--text">Compra tus productos de las mejores marcas</h1>
        <h5 class="font-weight-regular title grey--text darken-1">
          Accede a más de
          <span class="regular success--text">10 tiendas</span> especialistas
        </h5>
        <v-layout row wrap align-center justify-center>
          <ImgMark :large="true" width="100" mark="santa-natura"/>
          <ImgMark :large="true" width="100" mark="yanvana"/>
          <ImgMark :large="true" width="100" mark="bio-naturista"/>
          <ImgMark :large="true" width="100" mark="inkanet"/>
          <v-flex xs12 sm12 md12>
            <div align="center">
              <v-btn @click="toProductos" depressed large color="accent white--text">Ver productos</v-btn>
            </div>
          </v-flex>
        </v-layout>
      </v-container>
    </v-container>
    <v-container grid-list-md>
      <v-layout row wrap>
        <v-flex md12 class="text-xs-center">
          <h1 class="font-weight-bold secondary--text">PIENSA FRESCO</h1>
          <h1 class="font-weight-bold success--text">PIENSA NATUED</h1>
        </v-flex>
        <CardHowWork
          image="herbal.svg"
          title
          content="Alejado el hombre de la naturaleza progresivamente pierde la salud"
        />
        <CardHowWork
          image="flower.svg"
          title
          content="El médico debe proceder imitando los medios que la naturaleza emplearía ordinariamente para curar la enfermedad"
        />
        <CardHowWork
          image="prescribe.svg"
          title
          content="El médico debe proceder imitando los medios que la naturaleza emplearía ordinariamente para curar la enfermedad"
        />
      </v-layout>
    </v-container>
    <v-container grid-list-sm text-sm-center py-5>
      <h1
        class="font-weight-medium text-md-center info-text"
      >Suscribite a nuestras nuevas publicaciones</h1>
      <br>
      <v-btn
        depressed
        large
        color="secondary"
        @click="suscribirse"
        href="https://docs.google.com/forms/d/e/1FAIpQLScXyexYEPObF233vFQYzQ2DCwn-Hl5znxZkiak-3wvgkH96_Q/viewform"
        target="_blank"
        rel="noopener noreferrer"
      >SUSCRIBIRSE</v-btn>
    </v-container>
    <v-container grid-list-md mt-5>
      <v-layout row wrap>
        <v-flex xs12 sm6 md6>
          <img src="~/assets/logo.svg" alt="natued-logo" width="60px" height="60x">
          <h1 class="body-2 font-weight-bold success--text">NATUED</h1>
          <h2 class="body-1 font-weight-regular">Permite que lo NATURAL sea MEDICINAL</h2>
        </v-flex>
        <v-flex xs12 sm6 md6>
          <h2 class="success--text">CONTACTO</h2>
          <p class="subheading font-weight-light">help@natued.com</p>
          <h2>REDES SOCIALES</h2>
          <v-layout row wrap>
            <v-flex xs1>
              <a
                href="https://www.facebook.com/app.natued/"
                target="_blank"
                rel="noopener noreferrer"
              >
                <img src="~/assets/facebook.svg" alt height="30px">
              </a>
            </v-flex>
          </v-layout>
        </v-flex>
      </v-layout>
    </v-container>
  </v-layout>
</template>

<script>
import CardHowWork from '~/components/CardHowWork.vue'
import CardFunction from '~/components/CardFunction.vue'
import ImgMark from '~/components/ImgMark.vue'

export default {
  head: {
    title: 'Natued',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: 'Medicina natural, aplicación de medicina natural'
      }
    ],
    noscript: [{ innerHTML: 'Body No Scripts', body: true }]
    // script: [
    //   { src: '/head.js' },
    //   // Supported since 1.0
    //   { src: '/body.js', body: true },
    //   { src: '/defer.js', defer: '' }
    // ]
  },
  components: {
    CardHowWork,
    ImgMark,
    CardFunction
  },

  data: () => ({
    content1:
      ' La aplicación móvil permite actualizar la ubicación, dirección, una breve descripción de la ubicación y además colocar una foto del recurso en su ubicación actual del lugar, todo con el objetivo de obtener una descripción clara de la ubicación del recurso.',
    content2:
      'El sistema permite realizar el control del recurso y un control detallado por piezas, indicando la ubicación correcta del recurso, totalmente lleno, uso correcto y además las observaciones recurrentes a cada pieza como rotura, rajadura, pintas, entre otras.',
    content3:
      'La aplicación móvil permita registrar el mantenimiento o reparación que se realice al recurso, como limpiezas de pintas, cambio de piezas, reparación de piezas, entre otras.'
  }),
  methods: {
    toProductos() {
      this.$router.push('/productos')
      this.$ga.event({
        eventCategory: 'productosRevisados',
        eventAction: 'action',
        eventLabel: 'label',
        eventValue: 1
      })
    },
    toApp() {
      this.$ga.event({
        eventCategory: 'category',
        eventAction: 'action',
        eventLabel: 'label',
        eventValue: 1
      }),
        this.$ga.event('click', 'action', 'label', 123)
      this.$ga.event('aplicacion', 'action', 'label', 123)
      this.$ga.event({
        eventCategory: 'aplicacion',
        eventAction: 'action',
        eventLabel: 'label',
        eventValue: 1
      })
      this.$router.push('/app')
    },
    suscribirse() {
      this.$ga.event({
        eventCategory: 'suscribirse',
        eventAction: 'action',
        eventLabel: 'label',
        eventValue: 1
      })
    }
  }
}
</script>
<style>
.conta {
  height: 500px;
}
.img-home {
  width: 100%;
  height: auto;
}
.span-h2 {
  color: rgb(92, 202, 201);
}
.span-h2esivamente pierde la salud:hover {
  color: rgb(251, 45, 48);
}
.card-rounder {
  border-radius: 0.8rem;
}
.img-logo {
  -webkit-filter: grayscale(1);
  filter: grayscale(1);
}
</style>

