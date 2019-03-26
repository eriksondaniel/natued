<template>
  <v-flex
    xs12
    sm6
    md4
  >
    <v-layout
      row
      wrap
    >
      <v-flex
        xs3
        sm3
        md3
      >
        <img
          :src="image"
          alt=""
          width="60"
        >
      </v-flex>
      <v-flex
        xs9
        sm9
        md9
      >
        <span class="title font-weight-black">{{ title }}</span>
        <h4 class="grey--text"> {{ content }} </h4>
      </v-flex>
    </v-layout>
  </v-flex>
</template>

<script>
export default {
  name: 'CardHowWork',
  props: {
    content: {
      type: String,
      required: true
    },
    image: {
      type: String,
      required: true
    },
    title: {
      type: String,
      required: true
    }
  }
}
</script>

<style>
.number-color {
  color: lightgrey;
}
</style>
