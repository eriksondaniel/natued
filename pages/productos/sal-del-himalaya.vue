<template>
  <v-container grid-list-md>
    <v-layout row wrap>
      <v-flex md12>
        <v-img
          src="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/sal-del-himalaya.jpg?alt=media&token=255d12b6-91e6-4223-9e56-ff027973520d"
          width="500px"
        />
      </v-flex>
      <v-flex md12>
        <h1>Sal del Himalaya</h1>
        <p
          class="headline font-weight-light"
        >Nos referiremos a la sal del Himalaya porque contiene algunas propiedades minerales adicionales con respecto a otras sales, pero de hecho podrías utilizar sal marina o sal común. La sal del Himalaya contiene numerosos oligoelementos con capacidad para nutrir y regenerar la piel. Una de las aplicaciones más útiles y prácticas la encontramos a la hora de realizar exfoliaciones.</p>
        <p
          class="headline font-weight-light"
        >La sal es uno de los ingredientes que no debe faltar en la despensa de cosmética natural, y la exfoliación es una de sus aplicaciones más beneficiosas. Si quieres saber cómo hacer una exfoliación o peeling con Sales Naturales visita nuestro reportaje remedios caseros para exfoliar la piel.</p>
        <p
          class="headline font-weight-light"
        >También podemos incorporarla a los baños en tratamientos de spa caseros, especialmente si sufrimos algún tipo de alteración en la piel (como en el caso de dermatitis, por ejemplo), ya que el agua de mar y la sal alivian los síntomas considerablemente.</p>
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
