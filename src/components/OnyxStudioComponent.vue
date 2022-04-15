<template>
  <section class="bg-gradient-3 position-relative">
    <div class="container d-flex justify-content-center align-items-center min-vh-100">
      <div class="row w-100 pt-5">
        <div class="col-lg-12">
          <figure>
            <img class="img-fluid pt-5 position-absolute top-50 start-0 translate-middle w-40"
              src="@/assets/source/image/kardon-1.png" alt="front speaker image" />
          </figure>
          <div class=" wrapper text-black text-center position-absolute top-50 start-50 translate-middle">
            <h2 class="display-6 text-center pb-0 pb-xl-9 mb-4 ff-marcellus">
              Onyx Studio
            </h2>
            <div class="mb-4">
              <p class="text-center text-fade-black-2 fs-5 mb-1">Beautiful sound
                goes wireless</p>
              <p class="text-center text-fade-black-1 fs-6">Sconic,
                transportable, wireless speaker system</p>
            </div>
            <router-link class="btn btn-custom-2 text-uppercase px-4" to="#">buy now</router-link>
          </div>
          <figure>
            <img class="img-fluid pt-5 position-absolute top-50 start-100 translate-middle w-40"
              src="@/assets/source/image/kardon-2.png" alt="behind speaker image" />
          </figure>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "OnyxStudioComponent",
}
</script>