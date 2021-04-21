<template>
  <div class="section is-medium" id="img_custom">
    <div class="container">
      <div class="columns is-variable is-5" data-aos="fade-up" data-aos-delay="50">
        <div class="column">
          <h1 class="title mb-6 gradient-color is-uppercase">Calculate Your BMI</h1>
          <p class="subtitle mb-5 has-text-white">Our studio is fully equipped and ready to help you achieve your goals.</p>
          <p class="has-text-white">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur aliquam, diam quis tempor ultrices, sem lorem sollicitudin lorem, condimentum pulvinar.</p>
          <p class="has-text-white">
            Cras turpis risus, aliquet a elit sit amet, hendrerit scelerisque dolor. Phasellus vel tempor nisl. tempor ultrices, sem lorem sollicitudin lorem, mi tellus et justo condimentum pulvinar mi tellus et justo. Cras turpis risus, aliquet a elit sit amet, hendrerit scelerisque dolor. Phasellus vel tempor nisl. tempor ultrices, sem lorem sollicitudin lorem, mi tellus et justo condimentum pulvinar mi tellus et justo.
          </p>
        </div>
        <div class="column">
          <div class="card p-5">
            <form action="">
              <div class="field">
                <label class="label">Enter Your Weight in KG</label>
                <div class="control">
                  <input class="input" type="text" placeholder="Example - 70">
                </div>
              </div>
              <div class="field">
                <label class="label">Enter Your Height in Meters</label>
                <div class="control">
                  <input class="input" type="text" placeholder="Example - 1.80">
                </div>
              </div>
              <div class="field">
                <label class="label">Enter Your Age</label>
                <div class="control">
                  <input class="input" type="text" placeholder="Example - 32">
                </div>
              </div>
              <button class="button is-primary mt-5">Calculate BMI</button>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import AOS from 'aos'
export default {
  name: 'IMC',
  created () {
    AOS.init()
  }
}

</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import 'aos/dist/aos.css';

#img_custom {
  background-image: url(https://themes.krucial.com.au/fitnessgym-1/wp-content/uploads/sites/17/2017/02/homelayer-2-flipped.jpg?id=354) !important;
  background-position: center center;
  background-size: cover;
  width: 100%;
}

</style>
