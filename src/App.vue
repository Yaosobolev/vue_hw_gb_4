<template>
  <div id="app">
    <div class="container">
      <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
      <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
      <HeaderComp />
      <DetailsComp />
      <KitchenComp />
      <FooterComp />
    </div>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import FooterComp from './components/FooterComp.vue'
import HeaderComp from './components/HeaderComp.vue'
import DetailsComp from './components/DetailsComp.vue'
import KitchenComp from './components/KitchenComp.vue'


export default {
  name: 'App',
  components: {
    // HelloWorld,
    HeaderComp,
    DetailsComp,
    FooterComp,
    KitchenComp
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.container {
  display: flex;
  flex-direction: column;
  align-items: center;
}

</style>
