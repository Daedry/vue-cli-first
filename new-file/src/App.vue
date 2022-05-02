<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <titoloTitle msg="Lorem issssssssssssssssssssssssssssssssssssssss"/>
    <my-new-image />
    
  </div>
</template>

<script>
import titoloTitle from './components/titoloTitle.vue'
import MyNewImage from './components/MyNewImage.vue'


export default {
  name: 'App',
  components: {
    titoloTitle,
    MyNewImage
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
</style>
