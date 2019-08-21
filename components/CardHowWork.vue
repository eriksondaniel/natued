<template>
  <v-flex xs12 sm6 md4>
    <v-card flat class="card-rounder">
      <v-card-title primary-title/>
      <v-img contain :src="image" height="50px"/>
      <v-card-text class="text-xs-center">
        <h3 v-if="title" class="headline font-weight-medium">{{ title }}</h3>
        <p class="subheading font-weight-light">{{ content }}</p>
        <!-- <div>{{ content }}</div> -->
      </v-card-text>
    </v-card>
    <!-- <v-layout row wrap>
      <v-flex xs3 sm3 md3>
        <img :src="image" alt width="60">
      </v-flex>
      <v-flex xs9 sm9 md9>
        <span class="title font-weight-black">{{ title }}</span>
        <h4 class="grey--text">{{ content }}</h4>
      </v-flex>
    </v-layout>-->
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
.card-rounder {
  border-radius: 0.8rem;
}
</style>
