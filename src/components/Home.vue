<template>
  <div class="home container grellow-bg">
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
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
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

.container {
  border-width: 13px;
  border-style: solid;
  border-color:  #fef1cf;
  padding: 50px;
  margin-top: 100px;
}

</style>
