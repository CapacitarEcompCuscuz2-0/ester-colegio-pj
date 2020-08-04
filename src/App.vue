<template>
  <div id="app">
    <Navbar/>
    <div id="rota">
      <transition name="fade">
        <router-view></router-view>
      </transition>
    </div>
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
  @import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');
  body{
    margin: 0;
  }
  #app {
    font-family: 'Montserrat', sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
  }
  #rota{
    margin-top: 13.4vh;
  }
  .fade-enter-active, .fade-leave-active {
    transition: opacity 1.5s;
  }
  .fade-enter, .fade-leave-to{
    opacity: 0;
  }
</style>
