<template>
  <div id="app">
    <transition name="slide-left">
      <router-view></router-view>
    </transition>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
  .slide-left-enter-active, .slide-left-leave-active {
    transition: all .5s linear;
  }

  .slide-left-enter {
    transform: translateX(100%);
    opacity: 0;
  }

  .slide-left-leave-active {
    transform: translateX(-100%);
    opacity: 0;
  }
</style>
