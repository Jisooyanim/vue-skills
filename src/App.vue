<template>
  <div id="app">
    <Skills/>
  </div>
</template>

<script>
import Skills from './components/Skills.vue'

export default {
  name: 'App',
  components: {
    Skills,
  }
}
</script>

<style>
@import "https://cdn.jsdelivr.net/npm/animate.css@3.5.1";
@import "https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css"; 

  body {
    background-color: lightpink;
    font-family: 'Montserrat', sans-serif;
    display: grid;
    grid-template-rows: auto;
    justify-items: center;
    padding-top: 50px;
  }
  body, html {
    margin: 0;
    height: 100%;
  }
  #app {
      width: 50%;
  }

  nav {
    padding: 20px 20px 20px 0;
  }

  nav a {
    padding: 10px;
    text-decoration: none;
    background: #fff;
    border-radius: 3px;
    color: rgb(0, 110, 255);
    font-weight: bold;
    margin-right: 15px;
  }
</style>
