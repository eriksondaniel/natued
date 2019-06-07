<template>
  <v-flex
    xs12
    sm6
    md4
  >
    <v-card class="elevation-0">
      <nuxt-link
        :to="route"
        class="link"
      >
        <v-img
          :src="image"
          height="200px"
        />

        <v-card-title primary-title>
          <div>
            <h2 class="headline mb-0 font-weight-medium black--text">{{ title }}</h2>
            <h3 class="grey--text text--darken-1 font-weight-regular">{{ subTitle }}</h3>
          </div>
        </v-card-title>
      </nuxt-link>
      <v-list-tile avatar>
        <v-list-tile-avatar>
          <img src="https://cdn.vuetifyjs.com/images/lists/2.jpg">
        </v-list-tile-avatar>

        <v-list-tile-content>
          <v-list-tile-title v-html="autor"></v-list-tile-title>
          <v-list-tile-sub-title
            class="grey--text text--darken-1"
            v-html="date"
          ></v-list-tile-sub-title>
        </v-list-tile-content>
      </v-list-tile>

      <!-- <v-card-actions>
        <v-btn
          flat
          color="primary"
        >text</v-btn>
        <v-btn
          flat
          color="primary"
        >text</v-btn>
      </v-card-actions> -->
    </v-card>
  </v-flex>
</template>

<script>
export default {
  name: 'CardHowWork',
  props: {
    autor: {
      type: String,
      required: true
    },
    date: {
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
