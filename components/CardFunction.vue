<template>
  <v-flex xs12 sm6 md4>
    <v-card flat round class="success card-rounder">
      <v-card-title>
        <v-layout row wrap>
          <v-flex md2>
            <v-img :src="image" width="50px"/>
          </v-flex>
          <v-flex md10 class="white--text">
            <h3 class="headline">{{ title }}</h3>
            <h4 class="font-weight-light">{{ content }}</h4>
          </v-flex>
        </v-layout>
      </v-card-title>
    </v-card>
  </v-flex>
</template>

<script>
export default {
  name: 'CardFunction',
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
.card-rounder {
  border-radius: 0.8rem;
}
</style>
