<template>
  <v-flex md5>
    <v-card
      flat
      class="card-rounder"
    >
      <v-img src="https://cdn.vuetifyjs.com/images/cards/docks.jpg">
        <v-container
          fill-height
          fluid
        >
          <v-layout fill-height>
            <v-flex
              xs12
              align-end
              class="white--text"
            >
              <h4 class="font-weight-thin">Luis Guzman</h4>
              <h5 class="font-weight-thin">Mar 29, 2019 - 1 min</h5>
              <!-- <span class="headline">Top 10 Australian beaches</span> -->
              <v-flex
                py-5
                my-5
              />
              <v-flex
                py-5
                my-5
              />
              <nuxt-link to="/blog/medicina-natural">
                <h1 class="white--text font-weight-regular">Medicina Natural</h1>
              </nuxt-link>
              <v-divider class="white" />
            </v-flex>
          </v-layout>
        </v-container>
      </v-img>
    </v-card>
  </v-flex>
</template>

<script>
export default {}
</script>

<style>
.card-rounder {
  border-radius: 0.8rem;
}
</style>
