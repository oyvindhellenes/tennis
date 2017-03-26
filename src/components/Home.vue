<template>
  <div>
    <nav class=container>
      <ul class="nav nav-tabs">
        <li class="nav-item">
          <a class="nav-link" href="#">Om oss</a>
        </li>
        <li class="nav-item">
          <a class="nav-link active bold" href="#">Heim</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Meir info</a>
        </li>
      </ul>
    </nav>
    <div class="home container grellow-bg">
      <img src="../assets/tennisball.png" id="tennisball">
      <h1 class="beige">Bli med og støtt Noregs første folkefinansierte idrettsanlegg!</h1>
      <div class="progress beige-bg">
        <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="32" aria-valuemin="0" aria-valuemax="100" style="width: 32%">
          <p class="lead bold green">
            31 200kr
          </p>
        </div>
      </div>
      <div>
        <button type="button" class="btn btn-primary btn-lg beige green-bg bold">
          BLI MED!
        </button>
      </div>
      <img src="../assets/spacer.png" id="spacer">


    </div>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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

#tennisball {
  width: 300px;
  margin: auto;
  padding: 50px;
}

.nav-link {
  height: 100px;
  position: relative;
  top: 5px;
  background-color: #ebc733;
  border-style: none none solid none;
  border-color: black;
  border-width: 5px;
}

.nav-item a{
  color: black;
  font-size: 30px;
  padding-top: 25px;
}

.nav-item {
  margin: 0px 10px 0px 10px;
  width: 100%;
}

.nav-link:hover {
  border-style: solid solid none solid;
  border-color: black;
  border-width: 5px;
}

.nav-link.active {
  background-color: #fef1cf;
  border-style: solid solid none solid;
  border-color: black;
  border-width: 5px;
  position: relative;
  top: 5px
}

.nav-tabs {
  border-bottom: 5px solid black;
}

.nav-tabs .nav-link.active {
  color: black;
}

.progress-bar-animated {
  background-color: #ebc733;
  height: 40px;
}
.progress {
  margin-top: 50px;
  margin-bottom: 30px;
}

.progress p {
  margin-top: 10px;
}

.btn-lg {
  height: 80px;
}

.home {
  border-width: 13px;
  border-style: solid;
  border-color:  #fef1cf;
  padding: 50px;
}

</style>
