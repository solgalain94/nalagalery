<template>
  <HeaderComponent></HeaderComponent>
  <GaleriaComponent></GaleriaComponent>
</template>

<script>
import GaleriaComponent from './components/GaleriaComponent.vue'
import HeaderComponent from './components/HeaderComponent.vue'

export default {
  name: 'App',
  components: {
    GaleriaComponent,
    HeaderComponent
}
}
</script>

<style>
@import "./assets/css/styles.css";
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
