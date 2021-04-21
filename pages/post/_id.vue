<template>
  <section class="section">
    <h1 class="title">
      {{ post.title }}
    </h1>
    <h2 class="subtitle">{{ post.body }}</h2>
  </section>
</template>
<script>
export default {
  async asyncData ({ params, $axios, error }) {
    const id = params.id

    try {
      // Using the nuxtjs/http module here exposed via context.app
      const post = await $axios.$get(`https://jsonplaceholder.typicode.com/posts/${id}`)
      return { post }
    } catch (e) {
      error(e) // Show the nuxt error page with the thrown error
    }
  }
}

</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
