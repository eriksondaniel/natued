<template>
  <v-container grid-list-lg>
    <h1>Blog</h1>
    <v-layout
      row
      wrap
    >
      <CardBlog />
      <CardBlog />
      <CardBlog />
      <CardBlog />
    </v-layout>
  </v-container>
</template>

<script>
import CardBlog from '@/components/CardBlog'
export default {
  components: {
    CardBlog
  }
}
</script>

<style>
.img-blog {
  width: 100%;
  height: auto;
}

.img-blog-filter {
  -webkit-filter: sepia(1);
  filter: sepia(1);
}
</style>
