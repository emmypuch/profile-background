<template>
  <div class="userInfo">
    <div class="userInfo-list">
      <h1>Emmypuch</h1>
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
  position: relative;
  height: 172px;
  width: 694px;
  margin-top: 20%;
  padding: 15px 30px;
  background-color: #000000;
  background-image: linear-gradient(147deg, #000000 0%, #010332 74%);
  border-radius: 2px;
  box-shadow: 0 0 30px 0px rgb(0 0 0 / 10%);
  -webkit-box-shadow: 0 0 30px 0px rgb(0 0 0 / 10%);
  -moz-box-shadow: 0 0 30px 0px rgba(0, 0, 0, 0.1);
}

h1 {
  text-align: center;
  margin-top: 35px;

  font-size: 4rem;
  letter-spacing: 2px;
  background: -webkit-linear-gradient(#ffe98a, #d74177);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
</style>
