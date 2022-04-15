<template>
  <section class="bg-gradient-4">
    <div class="container d-flex justify-content-center align-items-center min-vh-100">
      <div class="row w-100 pt-5">
        <div class="col-lg-6">
          <figure>
            <img class="img-fluid mb-5 mb-lg-0 w-100 d-block mx-auto" src="@/assets/source/image/go.png"
              alt="hk go-play image" />
          </figure>
        </div>
        <div class=" col-lg-6 d-flex align-items-center">
          <div class="wrapper text-center text-lg-start">
            <h2 class="display-6 pb-0 pb-xl-9 mb-4 ff-marcellus">
              HK GO-Play
            </h2>
            <div class="mb-4">
              <p class="text-fade-2 fs-5 mb-1">SoundSticks Wireless</p>
              <p class="text-fade-1 fs-6">Wireless speaker system with
                Bluetooth connectivity</p>
            </div>
            <router-link class="btn btn-custom-1 text-uppercase px-4" to="#">buy
              now</router-link>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "GoPlayComponent",
}
</script>