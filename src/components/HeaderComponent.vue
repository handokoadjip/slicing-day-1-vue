<template>
  <header class="bg-gradient-1 min-vh-100 d-flex flex-column justify-content-center align-items-center">
    <nav class="navbar navbar-expand-lg fixed-top navbar-dark p-3 p-lg-4 ff-montserrat">
      <div class="container">
        <router-link class="navbar-brand" to="#">
          harman<span class="text-fade-1 fw-light">/</span>kardon'
        </router-link>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
          <ul class="navbar-nav text-uppercase d-flex align-items-center">
            <li class="nav-item px-4">
              <router-link class="nav-link fs-7" aria-current="page" to="#">products</router-link>
            </li>
            <li class="nav-item px-4">
              <router-link class="nav-link fs-7" to="#">about</router-link>
            </li>
            <li class="nav-item px-4">
              <router-link class="nav-link fs-7" to="#">blog</router-link>
            </li>
            <li class="nav-item px-4">
              <router-link class="nav-link fs-7" to="#">contact</router-link>
            </li>
            <li class="nav-item ps-3 pe-3">
              <router-link class="nav-link active fs-5" to="#">
                <i class="fas fa-search"></i>
              </router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <div class="container py-5">
      <div class="row">
        <div class="col-lg-12">
          <div class="wrapper text-center d-flex justify-content-center align-content-center position-relative">
            <figure>
              <img class="img-fluid mb-5 mb-lg-0 w-40 w-xxl-40 pt-5" src="@/assets/source/image/aura.png"
                alt="aura image" />
            </figure>
            <h1 class="display-3 pb-0 pb-xl-9 position-absolute top-50 start-50 translate-middle w-100 ff-marcellus">
              Legacy of Achivement</h1>
          </div>
          <p class="fs-4 text-center text-fade-1 leading-relaxed">
            harman kadon delivers beautiful sound b combining unmatched audio
            quality and iconic
            <br class="d-none d-md-block" />design to create a work of both art and sound
          </p>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
}
</script>

