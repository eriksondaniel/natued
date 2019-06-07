<template>
  <v-flex
    xs6
    sm3
    md3
  >
    <img
      v-if="mark == 'santa-natura'"
      src="~/assets/santa-natura.jpg"
      alt=""
      :width="width"
      class="img-logo"
    >
    <img
      v-else-if="mark == 'yanvana'"
      src="~/assets/yanvana.png"
      alt=""
      :width="width"
      class="img-logo"
    >
    <img
      v-else-if="mark == 'bio-naturista'"
      src="~/assets/bio-naturista.png"
      alt=""
      :width="width"
      class="img-logo"
    >
    <img
      v-else-if="mark == 'inkanet'"
      src="~/assets/inkanat.png"
      alt=""
      :width="width"
      class="img-logo"
    >
  </v-flex>
</template>

<script>
export default {
  name: 'ImgMark',
  props: {
    width: {
      type: String,
      required: true
    },
    mark: {
      type: String,
      required: true
    },
    large: {
      type: Boolean,
      required: true
    }

    // date: {
    //   type: String,
    //   required: true
    // },
    // title: {
    //   type: String,
    //   required: true
    // },
    // subTitle: {
    //   type: String,
    //   required: true
    // },
    // route: {
    //   type: String,
    //   required: true
    // },
    // image: {
    //   type: String,
    //   required: true
    // }
  },
  methods: {
    markImage: item => {
      var route
      switch (item) {
        case 'santa-natura':
          route = '~/assets/santa-natura.jpg'
          return route
          break
        case 'yanvana':
          return '~/assets/yanvana.jpg'
          break
        case 'bio-naturista':
          return '~/assets/bio-naturista.jpg'
          break
        case 'inkanet':
          return '~/assets/inkanet.jpg'
          break
        default:
          break
      }
    }
  }
}
</script>