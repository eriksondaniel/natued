<template>
  <v-container grid-list-lg>
    <v-layout row wrap align-center justify-center align-content-center>
      <v-flex md12>
        <h1>Productos</h1>
      </v-flex>
      <CardProducto
        title="Algas"
        sub-title="Las algas son un ingrediente depurativo que se utiliza con frecuencia en tratamientos anticelulíticos, o en tratamiento rejuvenecedores."
        route="productos/algas"
        image="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/algas.jpg?alt=media&token=d421f27d-c5f9-4547-9cc0-de038b6b8ec1"
        :marks="[{'name':'santa-natura'},{'name':'yanvana'}]"
        category="Piel"
      />

      <CardProducto
        title="Cera de Abejas"
        sub-title="La cera de abejas es un elemento esencial a la hora de elaborar cremas naturales."
        route="productos/cera-de-abejas"
        image="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/cera-de-abejas.jpg?alt=media&token=f19793dd-6264-42e1-8737-59f6b8f44d79"
        :marks="[{'name':'santa-natura'}]"
        category="Gripe"
      />
      <CardProducto
        title="Sal del Himalaya"
        sub-title="Nos referiremos a la sal del Himalaya porque contiene algunas propiedades minerales adicionales con respecto a otras sales, pero de hecho podrías utilizar sal marina o sal común. "
        route="productos/sal-del-himalaya"
        image="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/sal-del-himalaya.jpg?alt=media&token=255d12b6-91e6-4223-9e56-ff027973520d"
        :marks="[{'name':'bio-naturista'},{'name':'yanvana'}]"
        category="Piel"
      />
    </v-layout>
  </v-container>
</template>

<script>
import CardProducto from '@/components/CardProducto'
export default {
  head: {
    title: 'Natued - Productos',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content:
          'Productos de Natued, encuentra las los mejores consejos de medicina natural'
      }
    ]
  },
  components: {
    CardProducto
  }
}
</script>

<style></style>
