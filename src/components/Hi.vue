<template>
  <div class="hi">
    <h1>{{ msg }}</h1>
    <router-link to="/">Go to Hello Page</router-link>
  </div>
</template>

<script>
export default {
  name: 'hi',
  data () {
    return {
      msg: 'Welcome to Hi Page'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .hi {
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    background-color: #693;
  }
</style>
