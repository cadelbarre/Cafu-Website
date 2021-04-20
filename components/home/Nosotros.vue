<template>
  <section class="section is-medium">
    <div class="container">
      <h1 class="title is-uppercase gradient-color"> our Classes</h1>
      <div class="columns is-variable is-5">
        <div class="column" v-for="i in 3" :key="i">
          <figure>
            <img src="https://krucial-themes-media.s3.ap-southeast-2.amazonaws.com/wp-content/uploads/sites/17/2017/02/21041539/service2.jpg" alt="">
            <figcaption class="is-overlay is-flex is-justify-content-center is-align-items-center is-flex-direction-column">
              <h1 class="has-text-white is-uppercase title">Weights Training</h1>
              <NuxtLink to="/about" class="has-text-white is-italic">View more</NuxtLink>
            </figcaption>
          </figure>
          <p class="mt-3">Lorem ipsum dolor, sit amet consectetur, adipisicing elit. Nesciunt vero quisquam, voluptas. Eaque ratione magnam, debitis mollitia nesciunt consequatur facere ea, corrupti fugit dicta at enim sunt blanditiis nostrum. Doloribus.</p>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: 'Nosotros'
}

</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
figure {
  position: relative;

  .title:not(:last-child) {
    margin-bottom: 0px !important;
    font-size: 24px !important;
  }

  .is-overlay {
    opacity: 0;
    height: 97%;
    background: rgb(27, 27, 27);
    background: linear-gradient(0deg, rgba(27, 27, 27, 0.9) 0%, rgba(255, 255, 255, 0) 100%);
    transition: all 0.5s ease;

    &:hover {
      opacity: 1;
    }

    &>* {
      transform: translateY(100px);
      transition: all 0.5s ease;
    }

    &:hover>* {
      transform: translateY(0px);
    }

  }

}

</style>
