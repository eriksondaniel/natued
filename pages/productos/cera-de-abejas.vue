<template>
  <v-container grid-list-md>
    <v-layout row wrap>
      <v-flex md12>
        <v-img
          src="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/cera-de-abejas.jpg?alt=media&token=f19793dd-6264-42e1-8737-59f6b8f44d79"
          width="500px"
        />
      </v-flex>
      <v-flex md12>
        <h1>Cera de abejas</h1>
        <p
          class="headline font-weight-light"
        >La cera de abejas es un elemento esencial a la hora de elaborar cremas naturales. Es muy resistente al paso del tiempo, es antioxidante y además de hidratar la piel, nos ayuda a conseguir una textura de crema en nuestros productos naturales de belleza.</p>
        <p
          class="headline font-weight-light"
        >Hacer una crema natural con cera de abejas es lo más fácil del mundo, a penas te llevará unos minutos y podrás sustituir definitivamente las cremas industriales llenas de sustancias químicas por un producto natural hidratante lleno de propiedades beneficiosas para la piel.</p>
        <p
          class="headline font-weight-light"
        >Si quieres saber cómo hacerla, visita nuestro artículo cómo hacer crema natural con cera de abejas y aceite de oliva.</p>
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
