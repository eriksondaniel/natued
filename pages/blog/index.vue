<template>
  <v-container grid-list-lg>
    <v-layout row wrap>
      <CardBlog
        autor="Dr. Ilche Park"
        date="Jun 8, 2019 - 2 min"
        title="Zanahoria y sus propiedades medicinales"
        sub-title="Te damos la receta del mejor extracto de zanahoria que te protegen de las enfermedades en el invierno"
        route="/blog/zanahoria-y-sus-propiedades-medicinales"
        image="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/zanahorias.jpg?alt=media&token=f0cdba04-6909-4360-bf6e-9b597cd6b056"
      />
      <CardBlog
        autor="Dr. Ilche Park"
        date="May 25, 2019 - 2 min"
        title="Propiedades curativas de la salvia"
        sub-title="Hoy te mencionamos 6 propiedades curativas de la salvia:"
        route="blog/propiedades-curativas-de-la-salvia"
        image="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/sabia.png?alt=media&token=07ae1040-89ce-496a-97c2-1cc9a194da60"
      />
      <CardBlog
        autor="Dr. Ilche Park"
        date="May 11, 2019 - 2 min"
        title="!Mejora la salud de tus globos oculares!"
        sub-title="Hoy no hablaremos de muchos productos que te ayudarán a tu salud sino uno en específico."
        route="blog/mejora-la-salud-de-tus-globos-oculares"
        image="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/globs-oculares.png?alt=media&token=470d27fe-5c89-4023-9917-5715e98b1563"
      />
      <CardBlog
        autor="Dr. Ilche Park"
        date="May 4, 2019 - 2 min"
        title="Lista de 10 alimentos anticancerigenos que puedes llevar al trabajo"
        sub-title="Tomar alimentos anticancerígenos como las algas, setas, frutos secos o cítricos puede ayudar a prevenir el cáncer, una enfermedad que es acusada en gran medida por el estilo de vida"
        route="blog/alimentos-anticancerigenos-que-puedes-llevar-al-trabajo"
        image="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/anticancerigenos.png?alt=media&token=bfcd0134-54e1-4b85-9d9b-7b6ea6dd9599"
      />
      <CardBlog
        autor="Dr. Miguelon Espinoza"
        date="Abr 22, 2019 - 2 min"
        title="Mejores productos naturales para el cuidado del cabello"
        sub-title="El limón y el aceite de oliva para un cuero cabelludo irritable y con caspa"
        route="blog/mejores-productos-naturales-para-el-cuidado-del-cabello"
        image="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/productos-naturales-para-el-cabello.jpg?alt=media&token=e9b571c9-16cc-47fa-9392-5ae6b6ac6a24"
      />
      <CardBlog
        autor="Miguelon Espinoza"
        date="Abr 12, 2019 - 1 min"
        title="Jarabe natural a base de miel de abeja y kión previene el asma'"
        sub-title="Las personas asmáticas, en especial los niños, son sensibles a la llegada del otoño, época en que se incrementan sus visitas a los hospitales."
        route="blog/jaraba-natural-a-base-de-miel-de-abeja-y-kion-previene-el-asma"
        image="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/jarabe_de_miel_ajo_kion.jpg?alt=media&token=43fbdded-3f0e-44c7-8d29-b46f67b0435a"
      />
      <CardBlog
        autor="Miguelito Espinoza"
        date="Abr 8, 2019 - 2 min"
        title="Cuba desarrolla proyectos de investigación en medicina natural"
        sub-title="Cuba desarrolla actualmente 44 proyectos de investigación dentro del Programa de Medicina Natural y Tradicional (MNT), según se conoció hoy durante la convención internacional 'Calixto García' sobre ciencias de la salud que se celebra esta semana en La Habana."
        route="blog/cuba-desarrolla-proyectos-investigación-medicina-natural"
        image="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/cuba-proyectos-investigacio%CC%81n.jpg?alt=media&token=4c2cdda7-ade5-4a0e-a443-f988777f73c7"
      />
      <CardBlog
        autor="Dr. Miguelon Espinoza"
        date="Mar 29, 2019 - 1 min"
        title="¿Qué es medicina natural?"
        sub-title="Medicina alternativa es toda práctica que afirma tener los efectos sanadores de la medicina pero que no está apoyada por..."
        route="blog/medicina-natural"
        image="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/medicina-natural.jpg?alt=media&token=aef53a84-6e2c-4539-bc63-88ed12ccdeca"
      />
      <CardBlog
        autor="Equipo Natued"
        date="Mar 25, 2019 - 1 min"
        title="¿Quienes somos?"
        sub-title="Somos una startup que busca proponer una alternativa al cuidado de la salud, a travez de nuestra aplicación móvil"
        route="blog/quienes-somos"
        image="https://firebasestorage.googleapis.com/v0/b/natued-app.appspot.com/o/herbal.png?alt=media&token=fa6846b9-880d-4739-89f9-c2766277c92a"
      />
    </v-layout>
  </v-container>
</template>

<script>
import CardBlog from '@/components/CardBlog'
export default {
  head: {
    title: 'Natued - Blog',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content:
          'Blog de Natued, encuentra las los mejores consejos de medicina natural'
      }
    ]
  },
  layout: 'blog',
  components: {
    CardBlog
  }
}
</script>

<style></style>
