<template>
  <div>
      <h1 class="beige bold" id="title">Bli med og støtt Noregs første folkefinansierte tennisbane i Førde!</h1>
      <img src="../assets/banner-yellow.png" id="banner">
      <h4 class="beige p">Vi i Førde Tennisklubb har jobba i over seks år for å kunne bygge ei flunkande ny tennisbane i Førde.
        No treng vi berre 100 000 kroner for å sette i gong med bygginga.
        Så bli med og støtt Noregs første folkefinansierte tennisbane!</h4>
      <img src="../assets/tennisball.png" id="tennisball">
      <h4 class="beige p">Så langt har vi samla inn 31200 på berre 5 dagar:</h4>
      <img src="../assets/racket.png" id="racket">
      <div class="progress beige-bg">
        <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="32" aria-valuemin="0" aria-valuemax="100" style="width: 32%">
          <p class="lead bold green">
            31 200kr
          </p>
        </div>
      </div>

      <div class="small-container beige-bg">
        <h3 class="bold blue">
          Støtt oss med vipps eller nettbank
        </h3>
        <img src="../assets/vipps_logo.png" id="vipps1">
        <h4 class="blue p">
          Vil du være med å folkefinansiere Tennisbane i Førde så kan du sende ønskeleg beløp på Vipps eller Nettbank.
        </h4>
        <h2 class="blue bold">Vipps nummer: 17722</h2>
        <h2 class="blue bold">Kontonummer: 15037510944</h2>
        <h4 class="blue p">PS: Hugs å merk donasjonen med navn slik at vi enkelt kan ta kontakt dersom det blir nødvendig. Dersom prosjektet skulle skjære seg eller prosjektet ikkje er påbegynt innan to år så vil du bli refundert fullt beløp.</h4>
        <div><img src="../assets/vipps1.jpg" id="vipps1"></div>
      </div>
      <img src="../assets/spacer.png" id="spacer">
  </div>
</template>

<script>
let product = {
  name: 'Moby Dick',
  description: 'I love whales',
  amount: 100000 // 100$ in cents
}
export default {
  name: 'app',
  data () {
    return product
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

#banner {
  width: 100%;
  border-style: solid;
  border-width: 5px;
  border-color: #fef1cf;
  border-radius: 10px;
  margin-bottom: 30px;
}

#tennisball {
  width: 200px;
  margin: auto;
  padding: 30px;
}

#racket {
  width: 300px;
  margin: auto;
  padding: 30px;
}

#vipps1 {
  width: 300px;
  margin: auto;
  margin-bottom: 30px;
  padding: 0px;
  border-radius: 10px;
}

#title {
  position: relative;
  padding: 20px;
  text-shadow: 2px 2px 0px black;
  font-size: 50px;

}

.small-container {
  padding: 20px;
  border-radius: 10px;
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


</style>
