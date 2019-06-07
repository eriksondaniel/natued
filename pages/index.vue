<template>
  <v-container>
    <v-container grid-list-md py-4 fluid>
      <v-layout row wrap align-center justify-center class="conta">
        <v-flex xs12 sm6 md5>
          <h2 class="display-1">Permite</h2>
          <h2 class="display-1">
            que lo
            <span class="font-weight-bold span-h2">NATURAL</span>
          </h2>
          <h2 class="display-1">
            sea
            <span class="font-weight-bold span-h2">MEDICINAL</span>
          </h2>
          <br>
          <h3 class="subheading">¡Descarga la app!</h3>
          <v-layout row wrap>
            <v-flex xs6 sm6 md4 py-3>
              <a
                href="https://play.google.com/store/apps"
                target="_blank"
                rel="noopener noreferrer"
              >
                <img src="google-play.svg" alt="Busca la aplicación en Google Play" height="40">
              </a>
            </v-flex>
            <v-flex xs6 sm6 md4 py-3>
              <a
                href="https://www.apple.com/la/ios/app-store/"
                target="_blank"
                rel="noopener noreferrer"
              >
                <img src="app-store.svg" alt="Busca la aplicación en App Store" height="40">
                <!-- https://dribbble.com/andrschk 
                https://cdn.dribbble.com/users/1062785/screenshots/6059370/healthcare-landing_4x.png
                https://cdn.dribbble.com/users/1062785/screenshots/6004265/healthcare-dashboard_4x.png
                https://cdn.dribbble.com/users/1062785/screenshots/5940935/healthcare__4x.png
                -->
              </a>
            </v-flex>
          </v-layout>
        </v-flex>
        <v-flex xs12 sm6 md7>
          <img src="image.png" alt="Natued" width="600" class="img-home">
        </v-flex>
      </v-layout>
    </v-container>
    <v-divider dropzone/>

    <v-container grid-list-md>
      <v-layout row wrap>
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
    <v-divider dropzone/>
    <v-container grid-list-md>
      <v-layout row wrap>
        <v-flex md7>
          <img src="image-2.png" alt class="img-home">
        </v-flex>
        <v-flex md5>
          <v-layout column wrap>
            <v-flex xs12 sm12 md12 pa-4 mb-2>
              <h1 class="font-weight-bold accent--text">¿CÓMO FUNCIONA?</h1>
            </v-flex>
            <CardHowWork
              image="one.svg"
              title="Medicos especialistas"
              content="Responden tus preguntas y consultas medicas"
            />
            <CardHowWork
              image="two.svg"
              title="Compra productos naturales"
              content="Encuentra los productos de las mejores marcas"
            />
            <CardHowWork
              image="three.svg"
              title="Programa una cita"
              content="Encuentra un médico especialista en medicina natural"
            />
          </v-layout>
        </v-flex>
      </v-layout>
    </v-container>
    <v-divider dropzone/>
    <v-container grid-list-md>
      <h1>Compra tus productos de las mejores marcas</h1>
      <h5 class="subheading grey--text">
        Accede a más de
        <span class="regular black--text">10 tiendas</span> especialistas
      </h5>
      <v-layout row wrap align-center justify-center>
        <ImgMark :large="true" width="100" mark="santa-natura"/>
        <ImgMark :large="true" width="100" mark="yanvana"/>
        <ImgMark :large="true" width="100" mark="bio-naturista"/>
        <ImgMark :large="true" width="100" mark="inkanet"/>
        <v-flex xs12 sm12 md12>
          <div align="center">
            <v-btn depressed large color="primary" @click="toProductos">
              Ver productos
              <v-icon right dark>keyboard_arrow_right</v-icon>
            </v-btn>
          </div>
        </v-flex>
      </v-layout>
    </v-container>
    <v-divider dropzone/>
    <v-container grid-list-md>
      <v-layout row wrap>
        <v-flex xs12 sm6 md4>
          <v-hover>
            <v-card
              slot-scope="{ hover }"
              :class="`elevation-${hover ? 1 : 0}`"
              class="card-rounder"
            >
              <v-card-title primary-title>
                <img src="herbal.svg" alt="10" width="70">
              </v-card-title>
              <v-card-text>
                <h2
                  class="subheading"
                >Alejado el hombre de la naturaleza progresivamente pierde la salud</h2>
              </v-card-text>
            </v-card>
          </v-hover>
        </v-flex>
        <v-flex xs12 sm6 md4>
          <v-hover>
            <v-card
              slot-scope="{ hover }"
              :class="`elevation-${hover ? 1 : 0}`"
              class="card-rounder"
            >
              <v-card-title primary-title>
                <img src="flower.svg" alt="10" width="70">
              </v-card-title>
              <v-card-text>
                <h2
                  class="subheading"
                >El médico debe proceder imitando los medios que la naturaleza emplearía ordinariamente para curar la enfermedad</h2>
              </v-card-text>
            </v-card>
          </v-hover>
        </v-flex>
        <v-flex xs12 sm6 md4>
          <v-hover>
            <v-card
              slot-scope="{ hover }"
              :class="`elevation-${hover ? 1 : 0}`"
              class="card-rounder"
            >
              <v-card-title primary-title>
                <img src="prescribe.svg" alt="10" width="70">
              </v-card-title>
              <v-card-text>
                <h2
                  class="subheading"
                >El médico debe proceder imitando los medios que la naturaleza emplearía ordinariamente para curar la enfermedad</h2>
              </v-card-text>
            </v-card>
          </v-hover>
        </v-flex>
      </v-layout>
    </v-container>
    <v-container grid-list-md>
      <v-btn color="success" @click="toSs">Analitics</v-btn>
    </v-container>
    <v-divider dropzone/>
    <v-container grid-list-md>
      <v-layout row wrap align-center py-4>
        <v-flex md4>
          <h1>Descripción</h1>
        </v-flex>
        <v-flex md8>
          <h2
            class="subheading"
          >Natued es una plataforma multicanal de preguntas y respuestas la cual permite a sus usuarios formular preguntas relacionadas al campo de la salud anónimamente, las cuales son respondidas gratuitamente por profesionales en el área de la Medicina natural.</h2>
        </v-flex>
      </v-layout>
    </v-container>
    <v-divider dropzone/>
    <v-container grid-list-sm text-sm-center py-5>
      <h1
        class="font-weight-medium text-md-center info-text"
      >Suscribite a nuestras nuevas publicaciones</h1>
      <v-btn
        depressed
        large
        color="secondary"
        href="https://docs.google.com/forms/d/e/1FAIpQLScXyexYEPObF233vFQYzQ2DCwn-Hl5znxZkiak-3wvgkH96_Q/viewform"
        target="_blank"
        rel="noopener noreferrer"
      >SUSCRIBIRSE</v-btn>
    </v-container>
    <v-divider dropzone/>
    <v-container grid-list-sm text-sm-center py-5>
      <v-layout row wrap justify-center align-center>
        <v-flex xs12 sm12 md6>
          <h1 class="font-weight-medium text-md-center info-text">Descarga la App</h1>
          <h2>Disponible para Android y iOS</h2>
        </v-flex>
        <v-flex xs12 sm12 md3 py-4>
          <a href="https://play.google.com/store/apps" target="_blank" rel="noopener noreferrer">
            <img src="google-play.svg" alt="Busca la aplicación en Google Play" height="50">
          </a>
        </v-flex>
        <v-flex xs12 sm12 md3 py-4>
          <a
            href="https://www.apple.com/la/ios/app-store/"
            target="_blank"
            rel="noopener noreferrer"
          >
            <img src="app-store.svg" alt="Busca la aplicación en App Store" height="50">
            <!-- https://dribbble.com/andrschk 
                https://cdn.dribbble.com/users/1062785/screenshots/6059370/healthcare-landing_4x.png
                https://cdn.dribbble.com/users/1062785/screenshots/6004265/healthcare-dashboard_4x.png
                https://cdn.dribbble.com/users/1062785/screenshots/5940935/healthcare__4x.png
            -->
          </a>
        </v-flex>
      </v-layout>
    </v-container>
    <v-divider dropzone/>
    <v-container grid-list-md mt-5>
      <v-layout row wrap>
        <v-flex xs12 sm6 md6>
          <img src="~/assets/logo.svg" alt="natued-logo" width="60px" height="60x">
          <h1 class="body-2 font-weight-bold primary--text">NATUED</h1>
          <h2 class="body-1 font-weight-medium">Permite que lo NATURAL sea MEDICINAL</h2>
        </v-flex>
        <!-- <v-flex
          xs3
          sm3
          md3
        >
          <a href="http://www.disa.com.pe/">
            <img
              src="http://www.disa.com.pe/wp-content/uploads/2017/12/logo-disa-header.svg"
              alt="logo-disa"
              width="100"
            >
          </a>
        </v-flex>-->
        <v-flex xs12 sm6 md6>
          <h2>Contacto</h2>
          <span>help@natued.com</span>
          <h2>Sigue nuestras redes</h2>
          <v-layout column wrap>
            <v-flex xs1>
              <a
                href="https://www.youtube.com/channel/UCM5SS4IgRadI-qTzEVRuh8A"
                target="_blank"
                rel="noopener noreferrer"
              >
                <img
                  src="~/assets/youtube.svg"
                  alt="Busca la aplicación en Google Play"
                  height="50"
                >
              </a>
            </v-flex>
            <v-flex xs1>
              <a
                href="https://www.facebook.com/app.natued/"
                target="_blank"
                rel="noopener noreferrer"
              >
                <img
                  src="~/assets/facebook.svg"
                  alt="Busca la aplicación en Google Play"
                  height="40"
                >
              </a>
            </v-flex>
          </v-layout>
        </v-flex>
      </v-layout>
    </v-container>
  </v-container>
</template>

<script>
import CardHowWork from '~/components/CardHowWork.vue'
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
    ImgMark
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
    },
    toSs() {
      console.log('toss')
      this.$ga.event({
        eventCategory: 'category',
        eventAction: 'action',
        eventLabel: 'label',
        eventValue: 123
      }),
        this.$ga.event('click', 'action', 'label', 123)
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

