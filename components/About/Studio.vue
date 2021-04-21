<template>
  <section class="section is-medium">
    <div class="container">
      <div class="columns">
        <div class="column">
          <h1 class="title is-uppercase">
            about our studio
          </h1>
          <p>Morbi sem enim, rutrum et euismod varius, egestas eget orci. Sed luctus ex ut ipsum fermentum pellentesque. Phasellus nunc augue, efficitur eget viverra in, semper eu magna. Nulla facilisi. In non diam ac justo auctor venenatis. Sed massa est, cursus non magna a, aliquet scelerisque risus.</p>
          <ul class="ml-5" style="list-style-type:disc">
            <li v-for="i in 4" :key="i">Donec nibh orci, pulvinar nec est a, eleifend varius lacus. Phasellus tincidunt tellus lorem, a efficitur eros pellentesque vel. Cras condimentum ipsum ut eros lacinia iaculis.</li>
          </ul>
        </div>
        <div class="column">
          <figure>
            <img src="https://krucial-themes-media.s3.ap-southeast-2.amazonaws.com/wp-content/uploads/sites/17/2017/02/21041628/split-img.png" alt="">
          </figure>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: 'Studio'
}

</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
ul>li {
  &:not(:last-child) {
    margin-bottom: 8px;
  }

  font-size: 0.8rem;
  color: rgba(0, 0, 0, 0.8) !important;
}

</style>
