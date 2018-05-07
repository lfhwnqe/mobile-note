<template >
  <div id = "app" >
    <img src = "./assets/logo.png" >
    <ul >
      <li class = "first" >1</li >
      <li class = "second" >2</li >
      <li class = "third" >3</li >
    </ul >
    <router-view />
  </div >
</template >

<script >
  export default {
    name: 'App'
  }
</script >

<style scoped >
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }

  ul {
    height: 1rem;
  }

  .first {
    width: 3rem;
    background: red;
  }

  .second {
    width: 6rem;
    background: blue;
  }

  .third {
    width: 9rem;
    background: yellow;
  }
</style >
