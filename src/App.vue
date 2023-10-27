<template>
  <div id="app" class="container">
  <img alt="Vue logo" src="./assets/checklist.png" class="logo">
 
  <todo-list></todo-list>
  </div>
</template>

<script>

import TodoList from './components/TodoList.vue'

export default {
  name: 'App',
  components: {

    TodoList ,
  }
}
</script>

<style>

* {
  box-sizing: border-box;
  
}
body{
  background: rgb(238,174,202);
background: -moz-radial-gradient(circle, rgba(238,174,202,1) 0%, rgba(151,177,208,1) 100%);
background: -webkit-radial-gradient(circle, rgba(238,174,202,1) 0%, rgba(151,177,208,1) 100%);
background: radial-gradient(circle, rgba(238,174,202,1) 0%, rgba(151,177,208,1) 100%);
filter: progid:DXImageTransform.Microsoft.gradient(startColorstr="#eeaeca",endColorstr="#97b1d0",GradientType=1);
}
.container {
  max-width: 600px;
  margin: 120px auto;
  padding: 25px;
  border-radius:6px;
  box-shadow: 0px 10px 15px rgba(0, 0, 0, 0.1);
  background-color: rgba(116, 75, 75, 0.3);
  color: #222;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  margin-top: 80px;
  font-size: 20px;
  
}
.logo {
  display: block;
  margin: 2px auto;
  height: 60px;
}
</style>
