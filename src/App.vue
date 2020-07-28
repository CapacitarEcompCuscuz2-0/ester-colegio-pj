<template>
  <div id="app">
    <Navbar/>
    <transition name="fade">
      <router-view></router-view>
    </transition>
    <BannerVue/>
    <Sobre/>
    <Depoimentos/>
    <Resultados/>
    <Contato/>
    <!--<img alt="Vue logo" src="./assets/logo.png">-->
  </div>
</template>

<script>
import Navbar from './components/Navbar/Navbar.vue'
import BannerVue from './components/BannerVue/BannerVue.vue'
import Sobre from './components/Sobre/Sobre.vue'
import Depoimentos from './components/Depoimentos/Depoimentos.vue'
import Resultados from './components/Resultados/Resultados.vue'
import Contato from './components/Contato/Contato.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    BannerVue,
    Sobre,
    Depoimentos,
    Resultados,
    Contato,
  }
}
</script>

<style>
  body{
    margin: 0;
  }
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
  }
  .fade-enter-active, .fade-leave-active {
    transition: opacity 1.5s;
  }
  .fade-enter, .fade-leave-to{
    opacity: 0;
  }
</style>
