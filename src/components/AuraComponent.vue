<template>
  <section class="bg-gradient-5">
    <div class="container d-flex justify-content-center align-items-center min-vh-100">
      <div class="row w-100 pt-5">
        <div class="col-lg-6 d-flex align-items-center order-1 order-lg-0">
          <div class="wrapper text-black text-center text-lg-start">
            <h2 class="display-6 pb-0 pb-xl-9 mb-4 ff-marcellus">
              Aura
            </h2>
            <div class="mb-4">
              <p class="text-fade-black-2 fs-5 mb-1">Wireless Home Speaker
              </p>
              <p class="text-fade-black-1 fs-6">
                Delivers beautiful sound by combining unmathced quality <br class="d-none d-md-block" />
                and iconic design to create a work of both art and sound
              </p>
            </div>
            <router-link class="btn btn-custom-2 text-uppercase px-4" to="#">buy
              now</router-link>
          </div>
        </div>
        <div class="col-lg-6 order-0 order-lg-1">
          <figure>
            <img class="img-fluid mb-5 mb-lg-0 w-100 d-block mx-auto" src="@/assets//source/image/aura-white.png"
              alt="aura image" />
          </figure>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "AuraComponent",
}
</script>