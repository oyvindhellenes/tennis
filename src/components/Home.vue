<template>
  <div>
      <h1 class="beige bold" id="title">Bli med og støtt Noregs første folkefinansierte tennisbane i Førde!</h1>
      <img src="../assets/lokasjon.jpg" class="full-width frame">
      <h4 class="beige p">Vi i Førde Tennisklubb har jobba lenge for å kunne bygge ei flunkande ny tennisbane i Førde.
        No treng vi berre 100 000 kroner for å sette i gong med bygginga.
        Så bli med og støtt Noregs første folkefinansierte tennisbane!</h4>

      <img src="../assets/tennisball.png" id="tennisball">
      <h4 class="beige p bold">Så langt har vi samla inn<span class="bold-underscore"> 31200kr</span>, men vi treng framleis 68800kr. Kampanjen sluttar om <span class="bold-underscore">19 dagar!</span></h4>
      <div class="progress beige-bg">
        <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="32" aria-valuemin="0" aria-valuemax="100" style="width: 32%">
          <p class="lead bold black">
            31 200kr
          </p>
        </div>
      </div>
      <h2 class="beige bold">Slik fungerar kampanjen</h2>
      <h4 class="beige p">
        Pengane frå kampanjen går utelukkande til ei ny tennisbane. Ingenting av det som blir henta inn skal brukast til drift eller liknande.
        Dersom noko skulle skjære seg eller prosjektet ikkje er påbegynt innan to år så vil du bli refundert fullt beløp.
        Difor er det viktig at du merkar investeringa di med navn og epost slik at vi enkelt kan ta kontakt dersom det blir nødvendig.
      </h4>
      <br>
      <h4 class="beige p">
        Vi tar gjerne i mot stønad både frå privatpersonar og bedrifter. Alle som støttar oss med 200kr eller meir vil automatisk
        få gratis medlemskap i eit år. Merk overføringa med “nei takk”, dersom du ikkje ønskjer å bli registrert som medlem i klubben.
      </h4>
      <br>
      <h4 class="beige p">
        Spesielt generøse gåver vil bli foreviga med ingravering i skilt på bana. Alle som gjer 500kr eller meir vil bli
        lista opp som bidragsyter på eit skilt ved sia av bana. Gjer du 5000kr eller meir får du navnet eller bedrifta
        gravert på eit eige 40x30cm skilt.
      </h4>
      <br>
      <h4 class="beige p">
        Så kva ventar du på? Bli med å starte ein ny breddeidrett i Førde!
      </h4>
      <img src="../assets/racket.png" id="racket">
      <br>
      <div class="small-container beige-bg">
        <img src="../assets/vipps_logo.png" id="vipps1">
        <h2 class="bold blue">
          Støtt oss med vipps eller nettbank
        </h2>
        <h4 class="blue p padding-top-bottom">
          Vil du være med å folkefinansiere Tennisbane i Førde så kan du sende ønskeleg beløp på Vipps eller Nettbank.
        </h4>
        <h4 class="blue bold">Vipps nummer:</h4>
        <h2 class="blue bold borderbox">17722</h2>
        <div><img src="../assets/vipps1.jpg" id="vipps2"></div>
        <h4 class="blue p-center padding-top-bottom">(Kontonummer: <span class="bold-underscore"> 15037510944</span>)</h4>
        <h4 class="blue p">PS: Hugs å merk investeringa med navn og epost.</h4>
      </div>
      <br>
      <h4 class="beige p">
        Har du spørsmål om kampanjen eller noko anna? Ta gjerne kontakt på post@fordetennis.no eller 94055843.
      </h4>
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

#tennisball {
  width: 200px;
  margin: auto;
  padding: 30px;
}

#racket {
  width: 300px;
  margin: auto;
  padding: 30px;
  padding-top: 0px;
}

#vipps1 {
  width: 300px;
  margin: auto;
  padding: 0px;
  border-radius: 10px;
}

#vipps2 {
  width: 300px;
  margin: auto;
  margin-top: 20px;
  margin-bottom: 20px;
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

.borderbox {
  padding: 10px;
  border-color: #017272;
  border-width: 4px;
  border-style: solid;
  border-radius: 5px;
  width: 150px;
  margin: auto;
  margin-top: 20px;
  margin-bottom: 20px;
}


</style>
