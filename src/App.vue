<template>
  <div id="app">
    <user-information />
  </div>
</template>

<script>
import UserInformation from './components/UserInformation.vue'
export default {
  name: 'App',
  components: {
    UserInformation
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  @import url('https://fonts.googleapis.com/css2?family=Calligraffitti&display=swap');
}

#app {
  display: flex;
  justify-content: center;
  align-content: center;
  font-family: 'Calligraffitti', cursive;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: #f2f4ff;
  height: 100vh;
}
</style>
