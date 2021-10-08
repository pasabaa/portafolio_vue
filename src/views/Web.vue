<template>
    <div class="container-fluid">
        <div class="row vh-100">
            <div class="col-lg-4 col-12 bg-orange h-100 align-items-center d-flex justify-content-center">
                <div class="text-center">
                    <h1 class="display-1 fw-bolder text-black text-center">Proyectos</h1>
                    <h2 class="fw-bolder text-orange-secondary">Programación Web</h2>
                    <h4 class="fw-bolder">Sitios y proyectos web</h4>
                </div>

            </div>
            <div class="col-lg-8 col-12 bg-black text-orange h-100 justify-content-center align-items-center d-flex">
                <div class="row justify-content-between p-4">

                    <div class="col-lg-6 col-12">
                        <div class="card border-0 bg-black card-info p-4">
                            <h1 class="fw-bolder">CRUD con PHP</h1>
                            <p>Un sitio con un CRUD utilizando solamente PHP del lado del servidor, y el framework
                                Bootstrap, basado en un sistema de una tienda de ropa.</p>
                        </div>
                    </div>

                    <div class="col-lg-6 col-12">
                        <div class="card border-0 bg-black card-info p-4">
                            <h1 class="fw-bolder">CRUD con Frameworks</h1>
                            <p>Un sitio con un sistema basado en una tienda de articulos variados, ropa, electrónica,
                                muebles, etc. Utilizando los frameworks: Laravel y Bootstrap 4.</p>
                        </div>
                    </div>

                    <div class="col-lg-6 col-12 mt-4">
                        <div class="card border-0 bg-black card-info p-4">
                            <h1 class="fw-bolder">Carrito de compras</h1>
                            <p>Utilizando con un sistema basado en una tienda de electrónica con su respectivo CRUD,
                                donde el usuario puede colocar o eliminar productos de una cesta, para después realizar
                                una pago con PayPal. Utilizando los frameworks: Laravel, Vue.js y Bootstrap 4.</p>
                        </div>
                    </div>

                    <div class="col-lg-6 col-12 text-center align-items-center d-flex justify-content-center">
                        <router-link to="/unity">
                            <img src="../assets/img/icon/arrow-back-circle.svg" class="img-fluid next" width="44"
                                alt="">
                        </router-link>
                        <router-Link to="/social">
                            <img src="../assets/img/icon/arrow-forward-circle.svg" class="img-fluid next" width="44"
                                alt="">
                        </router-Link>
                    </div>

                </div>


            </div>
        </div>
    </div>
</template>