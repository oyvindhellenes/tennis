<template>
  <div>
      <br>
      <h1 class="beige bold" id="title">Bli med å bygg tennisbane i Førde!</h1>
      <img src="../assets/lokasjon.jpg" class="full-width frame">
      <br>
      <h4 class="beige p">Vi i Førde Tennisklubb har jobba lenge med å planlegge eit flunkande nytt tennisanlegg i Førde. I fjor starta vi med å søke om midlar, men vi fekk dessverre avslag.
      Det var eit hardt slag i trynet, men vi gir sjølvsagt ikkje opp og difor lanserar vi no ein kampanje der vi skal prøve å folkefinansiere to nye baner i Førde.
      Berre tenk over den store sosiale nytten som kjem med å investere i heimbyen din kontra eit nytt bad eller hagemøblar!
      For å komme i gang med bygginga er det estimert at vi treng omlag 100 000kr og dette målet håpar vi at DU kan hjelpe oss med å nå. Så bli med og invester i heimbygda di!

      </h4>
      <br>
      <div class="progress beige-bg">
        <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="32" aria-valuemin="0" aria-valuemax="100" style="width: 32%">
          <p class="lead bold black">
            31 200kr
          </p>
        </div>
      </div>
      <br>
      <h4 class="beige p bold">Så langt har vi samla inn<span class="bold-underscore"> 31 200kr</span>, men vi treng framleis 68 800kr. Kampanjen sluttar om <span class="bold-underscore">19 dagar!</span></h4>
      <br>
      <img src="../assets/racket.png" id="racket">
      <h2 class="beige bold">Slik fungerar kampanjen</h2>
      <br>
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
      <br>
      <div class="small-container beige-bg">
        <img src="../assets/vipps_logo.png" id="vipps1">
        <h2 class="bold blue">
          Støtt oss med vipps eller nettbank
        </h2>
        <br>
        <h4 class="blue p-center">Vipps nummer:</h4>
        <h2 class="blue bold borderbox">17722</h2>
        <div><img src="../assets/vipps1.jpg" id="vipps2"></div>
        <h4 class="blue p-center">Kontonummer:</h4>
        <h2 class="blue bold borderbox">15037 51 0944</h2>
        <h4 class="blue p-center">PS: Hugs å merk investeringa med navn og epost.</h4>
      </div>
      <br>
      <img src="../assets/tennisball.png" id="tennisball">
      <h4 class="beige p">
        Har du spørsmål om kampanjen eller noko anna? Ta gjerne kontakt på <a href="bardasnes@outlook.com">bardasnes@outlook.com</a> eller 918 81 992.
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

.small-container {
  padding: 20px;
  border-radius: 10px;
  width: 90%;
  margin: auto;
}

.progress-bar-animated {
  background-color: #ebc733;
  height: 40px;
}
.progress {
  width: 90%;
  margin: auto;
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
  width: 350px;
  margin: auto;
  margin-top: 20px;
  margin-bottom: 20px;
}


</style>
