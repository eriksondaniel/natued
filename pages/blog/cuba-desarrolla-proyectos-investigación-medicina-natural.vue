<template>
  <v-container grid-list-md>
    <v-flex md12>
      <h1
        class="display-1 mb-0 font-weight-medium black--text"
      >Cuba desarrolla proyectos de investigación en medicina natural</h1>
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
      >Cuba desarrolla actualmente 44 proyectos de investigación dentro del Programa de Medicina Natural y Tradicional (MNT), según se conoció hoy durante la convención internacional "Calixto García" sobre ciencias de la salud que se celebra esta semana en La Habana.</p>
      <p
        class="headline grey--text text--darken-1 font-weight-light"
      >En gran parte de estos proyectos participa el grupo estatal BioCubaFarma, que reúne 38 empresas productoras y comercializadoras de medicamentos, equipos y servicios de alta tecnología, explicó a medios oficiales el jefe del programa MNT del Ministerio cubano de Salud Pública, Johann Perdomo.</p>
      <p
        class="headline grey--text text--darken-1 font-weight-light"
      >Además, la industria farmacéutica de la isla, uno de los sectores más punteros de Cuba, elabora un total de 124 productos de medicina natural, incluidos en el cuadro básico de medicamentos, precisó el experto.</p>
      <p
        class="headline grey--text text--darken-1 font-weight-light"
      >Entre esos medicamentos figuran jarabes anticatarrales como el Imefasma; formulaciones de aloe, elaboradas a base de sábila, y el Vimang, un producto natural cubano que se extrae del árbol del mango, así como los aceites ozonizados o los preparados antianémicos Neotrofín y Ferrical.</p>
      <p
        class="headline grey--text text--darken-1 font-weight-light"
      >La producción local de esos medicamentos ha contado con la contribución de masa vegetal y derivados apícolas como la miel y propóleos, entre otros, explicó Perdomo.</p>
      <p
        class="headline grey--text text--darken-1 font-weight-light"
      >También indicó que hay 10 modalidades del programa MNT reguladas en Cuba, como la acupuntura; la fitoterapia, que usa plantas medicinales sin adición de otros componentes; la apiterapia, que se basa en productos apícolas con fines curativos; la homeopatía y la terapia floral.</p>
      <p
        class="headline grey--text text--darken-1 font-weight-light"
      >La medicina natural y tradicional recibió en 2015 el estatus de "especialidad médica" en Cuba, donde desde hace años se realizan diversas prácticas como la acupuntura o la terapia floral que se han profesionalizado con títulos y entrenamientos específicos.</p>
      <p
        class="headline grey--text text--darken-1 font-weight-light"
      >El desarrollo y la investigación en la medicina natural y tradicional, su enseñanza y generalización forman parte de un programa oficial del Ministerio de Salud, que incluye desde los consultorios comunitarios hasta los hospitales.</p>
      <p
        class="headline grey--text text--darken-1 font-weight-light"
      >Las farmacias de la isla dispensan asimismo una gran variedad de productos naturales alternativos para aliviar todo tipo de males, desde gripes hasta dolores reumáticos.</p>
    </v-flex>
    <div align="center">
      <v-flex md6>
        <v-img
          src="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/cuba-proyectos-investigacio%CC%81n.jpg?alt=media&token=4c2cdda7-ade5-4a0e-a443-f988777f73c7"
          img-blog
        />
      </v-flex>
    </div>
  </v-container>
</template>

<script>
export default {
  head: {
    title: 'Blog - Medicina Natural',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content:
          'Cuba desarrolla proyectos de investigación en medicina natural'
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
.img-blog {
  width: 50%;
  height: auto;
}
</style>
