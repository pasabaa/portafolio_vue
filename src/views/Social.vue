<template>
    <div class="container-fluid">
        <div class="row vh-100">
            <div class="col-12 bg-orange h-100 align-items-center d-flex justify-content-center">
                <div class="container">
                    <div class="text-center">
                        <h1 class="display-1 fw-bolder text-black">Social media</h1>
                        <h2 class="fw-bolder text-orange-secondary">Sigueme en mis redes sociales</h2>
                        <h4 class="fw-bolder">En estas podrás ponerte en contacto conmigo. ¡Gracias!</h4>
                    </div>

                    <div class="text-center mt-4">
                        <ul class="nav justify-content-center">
                            <li class="nav-item mx-4"><a class="nav-link" href="https://twitter.com/pablo_san_"><img
                                        src="../assets/img/icon/logo-twitter.svg" class="img-fluid" width="34"
                                        alt=""></a></li>
                            <li class="nav-item mx-4"><a class="nav-link"
                                    href="https://www.instagram.com/pasabaaa/"><img
                                        src="../assets/img/icon/logo-instagram.svg" class="img-fluid" width="34"
                                        alt=""></a></li>
                            <li class="nav-item mx-4"><a class="nav-link"
                                    href="https://www.reddit.com/user/PaSaball"><img
                                        src="../assets/img/icon/logo-reddit.svg" class="img-fluid" width="34"
                                        alt=""></a></li>
                            <li class="nav-item mx-4"><a class="nav-link" href="https://github.com/pasabaa"><img
                                        src="../assets/img/icon/logo-github.svg" class="img-fluid" width="34"
                                        alt=""></a></li>
                        </ul>

                        <div class="mt-4">
                            <router-link to="/web">
                                <img src="../assets/img/icon/arrow-back-circle-dark.svg" class="img-fluid next"
                                    width="44" alt="">
                            </router-link>
                            <router-Link to="/">
                                <img src="../assets/img/icon/arrow-forward-circle-dark.svg" class="img-fluid next"
                                    width="44" alt="">
                            </router-Link>
                        </div>


                    </div>
                </div>


            </div>

            <div class="col-12 text-center align-items-center d-flex justify-content-center bg-whitesmoke">

            </div>
        </div>
    </div>
</template>

<script>
export default {
  name:'Social',
  created(){
    document.title='Portafolio - Social'
  }
}
</script>