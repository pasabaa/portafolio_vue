<template>
<div class="container-fluid">
    <div class="row vh-100">
      <div class="col-lg-4 col-12 bg-orange h-100 align-items-center d-flex justify-content-center">
        <div class="text-center">
          <h1 class="display-1 fw-bolder text-black text-center">Pablo Sánchez</h1>
          <h4 class="fw-bolder text-orange-secondary">Portafolio</h4>
        </div>

      </div>
      <div class="col-lg-8 col-12 bg-black text-orange h-100 align-items-center d-flex justify-content-center">
        <div class="row justify-content-center align-items-center">
          <div class="col-lg-4 col-12">
            <div class="text-center p-0">
              <img class="img-fluid rounded-circle" src="../assets/img/pablo.jpg" alt="" width="300">
            </div>
          </div>
          <div class="col-lg-6 col-12">
            <div class="card border-0 bg-black" style="width: 24rem;">
              <h1 class="display-4 fw-bolder">Sobre mí</h1>
              <p>Mi nombre es Pablo Sánchez, soy un estudiante universitario en proceso para graduarse de la carrera
                Tecnologías de la Información y la Comunicación en el área, Entornos Virtuales y Negocios Digitales.</p>
            </div>
          </div>
          <div class="col-lg-2 col-12">
            <router-Link to="/unity">
              <img src="../assets/img/icon/arrow-forward-circle.svg" class="img-fluid next" width="64" alt="">
            </router-Link>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>