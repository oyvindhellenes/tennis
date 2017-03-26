<template>
  <div id="app" class="green-bg">
    <img src="./assets/header.png" id="header-img">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  height: 100vw;
}

body {
  margin: 0;
}

.yellow {
  color: #ebc733;
}

.green {
  color: #587636;
}

.grellow {
  color: #8c8d30;
}
.beige {
  color: #fef1cf;
}

.yellow-bg {
  background-color: #ebc733;
}

.green-bg {
  background-color: #587636;
}

.grellow-bg {
  background-color: #8c8d30;
}
.beige-bg {
  background-color: #fef1cf;
}

.bold {
  font-weight: bold;
}

#spacer {
  height: 20px;
  margin-top: 50px;
  margin-bottom: 50px;
  width: 100%;
}

#header-img {
  width: 100%;
  margin-bottom: 30px;
  box-shadow: 0px 15px 30px #000000;
}
</style>
