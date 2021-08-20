<template>
  <div class="userInfo">
    <div class="userInfo-list">
      <h1>emmypuch</h1>
    </div>
    <div class="left">
      <h4>HTML</h4>
    </div>
    <div class="bottom-right">
      <h4>VueJs</h4>
    </div>
    <div class="bottom-left">
      <h4>TailwindCss</h4>
    </div>
    <div class="top-right">
      <h4>CSS</h4>
    </div>
    <div class="nuxt">
      <h4>Nuxt <span style="color:#276174">Js</span></h4>
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
  position: relative;
  height: 80px;
  width: 450px;
  margin-top: 25%;
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
  line-height: 1em;
  font-size: 2rem;
  letter-spacing: 2px;
  background: -webkit-linear-gradient(#ffe98a, #d74177);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

div.left {
  position: absolute;
  left: 0px;
  top: 0;
  padding: 5px;
}

div.left h4 {
  color: #ff2525;
  font-size: 0.4rem;
  font-style: italic;
  transform-origin: 0 0;
  transform: rotate(-10deg);
}

div.bottom-right {
  position: absolute;
  right: 0px;
  bottom: 0;
  padding: 5px;
}

div.bottom-right h4 {
  color: #00ff5b;
  font-size: 0.4rem;
  font-style: italic;
  transform-origin: 0 0;
  transform: rotate(-20deg);
}

div.bottom-left {
  position: absolute;
  left: 0px;
  bottom: 0;
  padding: 5px;
}

div.bottom-left h4 {
  color: #1bcedf;
  font-size: 0.4rem;
  font-style: italic;
}

div.top-right {
  position: absolute;
  top: 0px;
  right: 0;
  padding: 5px;
}

div.top-right h4 {
  color: #ffe53b;
  font-size: 0.4rem;
  font-style: italic;
  transform-origin: 0 0;
  transform: rotate(-10deg);
}

div.nuxt {
  position: absolute;
  top: 40px;
  right: 50px;
}

div.nuxt h4 {
  color: #e7ecef;
  font-size: 0.4rem;
  font-style: italic;
  transform-origin: 0 0;
  transform: rotate(-5deg);
}

h3 {
  color: #00e1fd;
  font-style: oblique;
  font-size: 0.8rem;
  letter-spacing: 2px;
  margin-top: 10px;
  margin-bottom: 15px;
  text-align: center;
}
</style>
