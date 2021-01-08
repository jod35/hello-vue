<template>
  <div id="app">
    <Header v-bind:logo="logo"/>
    <Main v-bind:main="main"/>
    <About/>
    <Services/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import About from './components/About.vue'
import Services from './components/Services.vue'



export default {
  name: 'App',
  components: {
    Header,
    Main,
    About,
    Services,


  },
  data(){
    return{
      "main":"Hello welcome to my app",
      "logo":"Hello"
    }
  }
}
</script>

<style>
html{
  scroll-behavior: smooth;
}
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  width: 100%;
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
</style>
