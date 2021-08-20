<template>
  <div class="userInfo">
    <div class="userInfo-list">
      <h1>emmypuch</h1>
    </div>
    <div>
      <h3>FrontStack</h3>
    </div>
  </div>
</template>

<script>
export default {
  name: 'UserInformation'
}
</script>

<style scoped>
.userInfo {
  height: 80px;
  width: 400px;
  margin-top: 25%;
  padding: 10px 30px;
  background-color: #000000;
  background-image: linear-gradient(147deg, #000000 0%, #010332 74%);
  /* background-color: #000000;
  background-image: linear-gradient(147deg, #000000 0%, #04619f 74%); */
}

h1 {
  color: #e7ecef;
  text-align: center;
  line-height: 1em;
  letter-spacing: 10px;
  background: -webkit-linear-gradient(#ffe98a, #d74177);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-weight: 700;
}

h3 {
  color: #fff;
}
</style>
