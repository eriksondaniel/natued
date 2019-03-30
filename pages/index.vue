<template>
  <v-container fluid>
    <v-container
      grid-list-md
      py-4
      fluid
    >
      <v-layout
        row
        wrap
        align-center
        justify-center
        class="conta"
      >
        <v-flex
          xs12
          sm6
          md5
        >
          <h2 class="display-1">Permite</h2>
          <h2 class="display-1">que lo <span class="font-weight-bold span-h2"> NATURAL</span> </h2>
          <h2 class="display-1">sea <span class="font-weight-bold span-h2">MEDICINAL</span> </h2>
          <br>
          <h3 class="subheading">¡Descarga la app!</h3>
          <v-layout
            row
            wrap
          >
            <v-flex
              xs6
              sm6
              md4
              py-3
            >
              <a
                href="https://play.google.com/store/apps"
                target="_blank"
                rel="noopener noreferrer"
              >
                <img
                  src="google-play.svg"
                  height="40"
                >
              </a>
            </v-flex>
            <v-flex
              xs6
              sm6
              md4
              py-3
            >
              <a
                href="https://www.apple.com/la/ios/app-store/"
                target="_blank"
                rel="noopener noreferrer"
              >
                <img
                  src="app-store.svg"
                  height="40"
                >
                <!-- https://dribbble.com/andrschk 
                https://cdn.dribbble.com/users/1062785/screenshots/6059370/healthcare-landing_4x.png
                https://cdn.dribbble.com/users/1062785/screenshots/6004265/healthcare-dashboard_4x.png
                https://cdn.dribbble.com/users/1062785/screenshots/5940935/healthcare__4x.png
                -->
              </a>
            </v-flex>
          </v-layout>
        </v-flex>
        <v-flex
          xs12
          sm6
          md7
        >
          <img
            src="image.png"
            alt="image"
            width="600"
            class="img-home"
          >
        </v-flex>
      </v-layout>
    </v-container>
    <v-divider dropzone />

    <v-container grid-list-md>
      <v-layout
        row
        wrap
      >
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
    <v-divider dropzone />
    <v-container grid-list-md>
      <v-layout
        row
        wrap
      >
        <v-flex md7>
          <img
            src="image-2.png"
            alt=""
            class="img-home"
          >
        </v-flex>
        <v-flex md5>
          <v-layout
            column
            wrap
          >
            <v-flex
              xs12
              sm12
              md12
              pa-4
              mb-2
            >
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
    <v-divider dropzone />
    <v-container grid-list-md>
      <h1>Compra tus productos de las mejores marcas</h1>
      <h5 class="subheading grey--text">Accede a más de <span class="regular black--text">10 tiendas</span> especialistas </h5>
      <v-layout
        row
        wrap
        align-center
        justify-center
      >
        <v-flex
          xs6
          sm4
          md3
          pa-2
        >
          <img
            src="santa-natura.jpg"
            alt=""
            width="100"
            class="img-logo"
          >
        </v-flex>
        <v-flex
          xs6
          sm4
          md3
          pa-2
        >
          <img
            src="yanvakawa.png"
            alt=""
            width="100"
            class="img-logo"
          >
        </v-flex>
        <v-flex
          xs6
          sm4
          md3
          pa-2
        >
          <img
            src="bio-naturista.png"
            alt=""
            width="100"
            class="img-logo"
          >
        </v-flex>
        <v-flex
          xs6
          sm4
          md3
          pa-2
        >
          <img
            src="inkanat.png"
            alt=""
            width="100"
            class="img-logo"
          >
        </v-flex>
      </v-layout>
    </v-container>
    <v-divider dropzone />

    <v-container grid-list-md>
      <v-layout
        row
        wrap
      >
        <v-flex
          xs12
          sm6
          md4
        >
          <v-hover>
            <v-card
              slot-scope="{ hover }"
              :class="`elevation-${hover ? 1 : 0}`"
              class="card-rounder"
            >
              <v-card-title primary-title>
                <img
                  src="herbal.svg"
                  alt="10"
                  width="70"
                >
              </v-card-title>
              <v-card-text>
                <h2 class="subheading">Alejado el hombre de la naturaleza progresivamente pierde la salud</h2>
              </v-card-text>
            </v-card>
          </v-hover>
        </v-flex>
        <v-flex
          xs12
          sm6
          md4
        >
          <v-hover>
            <v-card
              slot-scope="{ hover }"
              :class="`elevation-${hover ? 1 : 0}`"
              class="card-rounder"
            >
              <v-card-title primary-title>
                <img
                  src="flower.svg"
                  alt="10"
                  width="70"
                >
              </v-card-title>
              <v-card-text>
                <h2 class="subheading">El médico debe proceder imitando los medios que la naturaleza emplearía ordinariamente para curar la enfermedad</h2>
              </v-card-text>
            </v-card>
          </v-hover>
        </v-flex>
        <v-flex
          xs12
          sm6
          md4
        >
          <v-hover>
            <v-card
              slot-scope="{ hover }"
              :class="`elevation-${hover ? 1 : 0}`"
              class="card-rounder"
            >
              <v-card-title primary-title>
                <img
                  src="prescribe.svg"
                  alt="10"
                  width="70"
                >
              </v-card-title>
              <v-card-text>
                <h2 class="subheading">El médico debe proceder imitando los medios que la naturaleza emplearía ordinariamente para curar la enfermedad</h2>
              </v-card-text>
            </v-card>
          </v-hover>
        </v-flex>
      </v-layout>

    </v-container>
  </v-container>
</template>

<script>
import CardHowWork from '~/components/CardHowWork.vue'

export default {
  head: {
    title: 'Natued',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: 'Natued - Natural medicine'
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
    CardHowWork
  },

  data: () => ({
    content1:
      ' La aplicación móvil permite actualizar la ubicación, dirección, una breve descripción de la ubicación y además colocar una foto del recurso en su ubicación actual del lugar, todo con el objetivo de obtener una descripción clara de la ubicación del recurso.',
    content2:
      'El sistema permite realizar el control del recurso y un control detallado por piezas, indicando la ubicación correcta del recurso, totalmente lleno, uso correcto y además las observaciones recurrentes a cada pieza como rotura, rajadura, pintas, entre otras.',
    content3:
      'La aplicación móvil permita registrar el mantenimiento o reparación que se realice al recurso, como limpiezas de pintas, cambio de piezas, reparación de piezas, entre otras.'
  })
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

