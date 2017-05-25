<template>
  <div id="app" class="yellow-bg">
    <img src="./assets/header2.png" id="header-img">
    <nav class=container id="navigation">
      <ul class="nav nav-tabs">
        <li class="nav-item" v-on:click="setActive">
          <router-link to="/om" id="om" class="nav-link">Om oss</router-link>
        </li>
        <li class="nav-item" v-on:click="setActive">
          <router-link to="/heim" id="heim" class="nav-link">Heim</router-link>
        </li>
        <li class="nav-item">
          <a class="nav-link" id="info" href="#">Meir info</a>
        </li>
      </ul>
    </nav>
    <div class="home container grellow-bg">
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
export default {
  name: 'app',
  mounted: function() {
    this.setActive()
  },
  methods: {
    setActive: function() {
      console.log('hei')
      let path = window.location.pathname.split( '/' )[1];
      setTimeout(() => {
        let item = document.getElementById(path);
        item.className += " active bold";
      }, 50);
    }
  }
}

</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

body {
  margin: 0;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  margin: 0 10px;
}

nav {
    margin-top: 100px;
}

.container {
  padding-right: 0px;
  padding-left: 0px;
}

.home {
  border-width: 13px;
  border-style: solid;
  border-color:  #fef1cf;
  padding: 50px 150px 500px 150px;

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

.blue {
  color: #017272;
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
  font-family: 'Lilita One' !important;
}

.p {
  font-family: 'Helvetica' !important;
  font-weight: lighter;
  text-align: left;
  padding-left: 40px;
  padding-right: 40px;
}

#navigation .nav-link {
  height: 100px;
  position: relative;
  top: 5px;
  background-color: #ebc733;
  border-style: none none solid none;
  border-color: black;
  border-width: 5px;
}

#navigation .nav-item a{
  color: black;
  font-size: 30px;
  padding-top: 25px;
}

#navigation .nav-item {
  margin: 0px 10px 0px 10px;
  width: 100%;
}

#navigation .nav-link:hover {
  border-style: solid solid none solid;
  border-color: black;
  border-width: 5px;
}

#navigation .nav-link.active {
  background-color: #fef1cf;
  border-style: solid solid none solid;
  border-color: black;
  border-width: 5px;
  position: relative;
  top: 5px
}

#navigation .nav-tabs {
  border-bottom: 5px solid black;
}

#navigation .nav-tabs .nav-link.active {
  color: black;
}

#spacer {
  height: 20px;
  margin-top: 50px;
  margin-bottom: 50px;
  width: 100%;
}

#header-img {
  width: 100%;
}
</style>
