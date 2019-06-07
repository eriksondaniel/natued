<template>
  <v-container grid-list-md>
    <v-layout row wrap>
      <v-flex md12>
        <v-img
          src="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/algas.jpg?alt=media&token=d421f27d-c5f9-4547-9cc0-de038b6b8ec1"
          width="500px"
        />
      </v-flex>
      <v-flex md12>
        <h1>Algas</h1>
        <p
          class="headline font-weight-light"
        >Las algas son un ingrediente depurativo que se utiliza con frecuencia en tratamientos anticelulíticos, o en tratamiento rejuvenecedores.</p>
        <p class="headline font-weight-light">
          Las algas son ricas en minerales y oligoelementos, pero sobre todo son ricas en yodo.
          El yodo estimula la glándula tiroides de manera que estimula el metabolismo.
          Por eso están completamente desaconsejadas en casos de hipertiroidismo (tanto ingeridas como aplicadas de forma externa).
        </p>
        <p class="headline font-weight-light">
          Las algas, introducidas de manera general en la dieta, adelgazan y depuran el organismo, además de aportar nutrientes muy necesarios para una correcta protección inmunológica.
          Aplicadas en la piel, depuran las capas profundas, estimulan el crecimiento celular y aportan nutrientes muy beneficiosos a la piel.
          Si quieres saber cómo hacer una mascarilla con algas, visita nuestro artículo mascarilla Casera de Wakame para producir Ácido Hialurónico.
        </p>
      </v-flex>
      <!-- <v-flex md12>
        <h2>Encuentra en las siguientes marcas</h2>
        {{ marks }}
        <v-layout row wrap align-center justify-center align-content-center>
          <v-flex v-for="i in marks" :key="i.name">
            <ImgMark :large="true" width="50" :mark="i.name"/>
          </v-flex>
        </v-layout>
      </v-flex>-->
    </v-layout>
  </v-container>
</template>

<script>
import ImgMark from '@/components/ImgMark'

export default {
  components: {
    ImgMark
  }
  // data: () => ({
  //   marks: "[{'name':'santa-natura'},{'name':'yanvana'}]"
  // })
}
</script>

<style>
</style>
