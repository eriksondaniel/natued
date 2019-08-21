<template>
  <v-flex xs12 sm6 md4>
    <nuxt-link :to="route" class="link">
      <v-card flat class="card-rounder">
        <v-img class="black--text" height="200px" :src="image"/>
        <v-card-title primary-title>
          <v-flex md12>
            <div align="center">
              <h2 class="headline mb-0 font-weight-medium grey--text text--darken-4">{{ title }}</h2>
              <h3 class="grey--text text--darken-2 font-weight-regular">{{ category }}</h3>
              <v-layout row wrap align-center justify-center align-content-center>
                <v-flex v-for="i in marks" :key="i.name">
                  <ImgMark :large="true" width="50" :mark="i.name"/>
                </v-flex>
              </v-layout>
            </div>
          </v-flex>
        </v-card-title>
      </v-card>
    </nuxt-link>
  </v-flex>
</template>

<script>
import ImgMark from '@/components/ImgMark'

export default {
  components: {
    ImgMark
  },
  name: 'CardHowWork',
  props: {
    // autor: {
    //   type: String,
    //   required: true
    // },
    // date: {
    //   type: String,
    //   required: true
    // },
    category: {
      type: String,
      required: true
    },
    title: {
      type: String,
      required: true
    },
    subTitle: {
      type: String,
      required: true
    },
    route: {
      type: String,
      required: true
    },
    image: {
      type: String,
      required: true
    },
    marks: {
      type: Array,
      required: true
    }
  }
}
</script>

<style>
.link:hover,
.link:visited,
.link:link,
.link:active {
  text-decoration: none;
}
.card-rounder {
  border-radius: 0.8rem;
}
</style>