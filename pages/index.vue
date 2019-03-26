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
                  src="https://app-leacoach.firebaseapp.com/static/media/google-play.49acf4fc.svg"
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
                  src="https://app-leacoach.firebaseapp.com/static/media/app-store.2a34124e.svg"
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
            src="https://cdn.dribbble.com/users/1062785/screenshots/5967607/responsive_design_4x.png"
            alt=""
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
          image="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/general%2Fdoctor.svg?alt=media&token=c2998a8c-f1ce-4933-a2f2-0e92b10ffe62"
          title="Medicos especialistas"
          content="Responden tus preguntas y consultas medicas"
        />
        <CardHowWork
          image="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/general%2Fmedicine.svg?alt=media&token=8adb8840-f948-4c65-8ba8-e575efb0835c"
          title="Compra productos naturales"
          content="Encuentra los productos de las mejores marcas"
        />
        <CardHowWork
          image="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/general%2Fmedical-research.svg?alt=media&token=f93bb0cd-b91d-4bc5-94b7-c997fe57a352"
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
            src="https://cdn.dribbble.com/users/1062785/screenshots/5940935/healthcare__4x.png"
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
              image="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/general%2Fone.svg?alt=media&token=071d7fd5-35a8-46ca-bd03-e8a252e68d9f"
              title="Medicos especialistas"
              content="Responden tus preguntas y consultas medicas"
            />
            <CardHowWork
              image="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/general%2Fthree.svg?alt=media&token=6c000de9-ad4a-42da-a916-98138ab9b681"
              title="Compra productos naturales"
              content="Encuentra los productos de las mejores marcas"
            />
            <CardHowWork
              image="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/general%2Fthree.svg?alt=media&token=6c000de9-ad4a-42da-a916-98138ab9b681"
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
            src="http://www.arequipacenter.com/up/source/large/santa_natura.jpg"
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
            src="https://image.jimcdn.com/app/cms/image/transf/none/path/s87b01a904e649b95/image/iad02b79648e3f30f/version/1505437672/image.png"
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
            src="http://bionaturista.com.pe/wp-content/uploads/2017/10/logo.png"
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
            src="https://planetahuerto-6f4f.kxcdn.com/estaticos/imagenes/marca/292/292.png"
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
          xs4
          sm4
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
                  src="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/general%2Fherbal.svg?alt=media&token=40eb2935-8a53-46d7-8e8a-c4f6e5fb862c"
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
          xs4
          sm4
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
                  src="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/general%2Fprescribe.svg?alt=media&token=0c7ddea9-6275-41f2-9185-c076c4154c0f"
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
          xs4
          sm4
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
                  src="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/general%2Fflower.svg?alt=media&token=fe1c91a8-04b1-4885-bdb4-9acd09308aa5"
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

