<template>
  <div class="home">
    <img alt="Algorithms & Programming" src="../assets/programming-windows-svgrepo-com.svg">
    <Main msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Main from '@/components/Main.vue'

export default {
  name: 'HomeView',
  components: {
    Main
  }
}
</script>

<style lang="scss" scoped>
  img {
    width: clamp(250px, 32%, 400px);
  }
</style>
