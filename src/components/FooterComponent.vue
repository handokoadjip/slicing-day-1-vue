<template>
  <footer>
    <div class="bg-gradient-6">
      <div class="container d-flex justify-content-center align-items-center">
        <div class="row w-100 pt-5">
          <div class="col-lg-3 mb-5 mb-lg-0">
            <div class="wrapper text-fade-1 text-center text-lg-start">
              <h3 class="fs-6 mb-4">Products</h3>
              <nav>
                <router-link
                  class="text-fade-1 text-decoration-none mb-1 d-block"
                  to="#"
                >Receivers & 3D Blu-ray</router-link>
                <router-link class="text-fade-1 text-decoration-none mb-1 d-block" to="#">Laudspeaker</router-link>
                <router-link class="text-fade-1 text-decoration-none mb-1 d-block" to="#">Headphones</router-link>
                <router-link class="text-fade-1 text-decoration-none mb-1 d-block" to="#">Wireless</router-link>
              </nav>
            </div>
          </div>
          <div class="col-lg-3 mb-5 mb-lg-0">
            <div class="wrapper text-fade-1 text-center text-lg-start">
              <h3 class="fs-6 mb-4">Conditions</h3>
              <nav>
                <router-link class="text-fade-1 text-decoration-none mb-1 d-block" to="#">Terms of use</router-link>
                <router-link class="text-fade-1 text-decoration-none mb-1 d-block" to="#">Privacy Policy</router-link>
              </nav>
            </div>
          </div>
          <div class="col-lg-3 mb-5 mb-lg-0">
            <div class="wrapper text-fade-1 text-center text-lg-start">
              <h3 class="fs-6 mb-4">About Us</h3>
              <nav>
                <router-link class="text-fade-1 text-decoration-none mb-1 d-block" to="#">Contact</router-link>
                <router-link
                  class="text-fade-1 text-decoration-none mb-1 d-block"
                  to="#"
                >About Harman Kardon</router-link>
                <router-link class="text-fade-1 text-decoration-none mb-1 d-block" to="#">History</router-link>
              </nav>
            </div>
          </div>
          <div class="col-lg-3 mb-5 mb-lg-0 d-none d-lg-block">
            <div class="wrapper text-fade-1 text-center text-lg-start position-relative">
              <figure class="position-absolute top-0 start-50 translate-middle w-100 pb-3">
                <img class="img-fluid" src="@/assets/source/image/hs-2.png" alt="headset image" />
                <figcaption class="fs-5 text-white text-center">
                  harman
                  <span class="text-fade-1 fw-light">/</span>kardon'
                </figcaption>
              </figure>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterComponent",
}
</script>