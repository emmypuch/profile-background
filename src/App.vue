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
  @import url('https://fonts.googleapis.com/css2?family=Rubik:ital,wght@0,400;1,800&display=swap');
}

#app {
  display: flex;
  justify-content: center;
  align-content: center;
  font-family: 'Rubik', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* background-color: #e7ecef; */
  /* margin-top: 60px; */
}
</style>
