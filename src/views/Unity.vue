<template>
  <div class="container-fluid">
    <div class="row vh-100">
      <div class="col-lg-4 col-12 bg-orange h-100 align-items-center d-flex justify-content-center">
        <div class="text-center">
          <h1 class="display-1 fw-bolder text-black text-center">Proyectos</h1>
          <h2 class="fw-bolder text-orange-secondary">Unity 3D</h2>
          <h4 class="fw-bolder">Videojuegos y aplicaciones</h4>
        </div>

      </div>
      <div class="col-lg-8 col-12 bg-black text-orange h-100 justify-content-center align-items-center d-flex">
        <div class="row justify-content-between p-4">

          <div class="col-lg-6 col-12">
            <div class="card border-0 bg-black card-info p-4">
              <h1 class="fw-bolder">Bomber Chicken</h1>
              <p>Es un juego Arcade con mecanicas parecidas al Pac-Man clásico, donde el jugador debe ir abriendose paso
                por el escenario, colocando bombas en para acabar con los enemigos.</p>
            </div>
          </div>

          <div class="col-lg-6 col-12">
            <div class="card border-0 bg-black card-info p-4">
              <h1 class="fw-bolder">Chicken Defense</h1>
              <p>Es un juego Tower Defense, donde se debe proteger una impresora 3D de los enemigos que apareceran en el
                escenario cada cierto tiempo, aumentando gradualmente la dificultad.</p>
            </div>
          </div>

          <div class="col-lg-6 col-12 mt-4">
            <div class="card border-0 bg-black card-info p-4">
              <h1 class="fw-bolder">App AR</h1>
              <p>Es un juego Arcade con mecanicas parecidas al Pac-Man clásico, donde el jugador debe ir abriendose paso
                por el escenario, colocando bombas en para acabar con los enemigos.</p>
            </div>
          </div>

          <div class="col-lg-6 col-12 mt-4">
            <div class="card border-0 bg-black card-info p-4">
              <h1 class="fw-bolder">App VR</h1>
              <p>Es un juego Tower Defense, donde se debe proteger una impresora 3D de los enemigos que apareceran en el
                escenario cada cierto tiempo, aumentando gradualmente la dificultad.</p>
            </div>
          </div>

          <div class="col-12 text-center mt-4">
            <router-link to="/">
              <img src="../assets/img/icon/arrow-back-circle.svg" class="img-fluid next" width="44" alt="">
            </router-link>
            <router-Link to="/web">
              <img src="../assets/img/icon/arrow-forward-circle.svg" class="img-fluid next" width="44" alt="">
            </router-Link>
          </div>

        </div>

        
      </div>
    </div>
  </div>
</template>