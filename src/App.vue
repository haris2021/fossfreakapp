<template>

  <div id="app">

   <div id="image">
    <img alt="fossfreaks logo" src="https://media-exp3.licdn.com/dms/image/C560BAQEhdySLOCp-Zw/company-logo_200_200/0/1596137012796?e=2159024400&v=beta&t=lmHaGE9474Vhv1pAKXJ9TyEDZsO5WKSCNY_qsPENMqc">
   </div>
    <HelloWorld msg="Welcome to fossfreaks"/>

  </div>


</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
  margin-bottom: 50px;
}

#image{
   margin-bottom: 10px;
   
}
</style>
