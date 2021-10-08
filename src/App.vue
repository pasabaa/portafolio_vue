<template>

<router-view v-slot="{Component}">
  <transition name="route" mode="out-in">
  <component :is="Component"></component>
  </transition>
</router-view>


</template>

<style>
  .route-enter-from {
    opacity: 1;
    background: #000;
    transform: translateX(100%);
  }

  .route-enter-active {
    transition: all .3s ease-out;
  }

.route-leave-to {
  opacity: 1;
  background: #000;
  transform: translateX(-100%);
}

.route-leave-active {
    transition: all .3s ease-in;
  }

</style>
