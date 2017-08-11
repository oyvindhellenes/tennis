<template>
  <div>
    <h1 class="beige bold" id="title">Om oss</h1>
    <div><img src="../assets/team.jpg" class="full-width frame"></div>
    <br>
    <img src="../assets/spacer.png" id="spacer">
    <h3 class="beige bold">Bård Nygård Åsnes / Leiar</h3>
    <div><img src="../assets/baard.jpg" class="profil frame"></div>
    <img src="../assets/spacer.png" id="spacer">
    <h3 class="beige bold">Anders Thommessen / Nest leiar</h3>
    <div><img src="../assets/anders.jpg" class="profil frame"></div>
    <img src="../assets/spacer.png" id="spacer">
    <h3 class="beige bold">Martin Savland / Økonomiansvarleg</h3>
    <div><img src="../assets/martin.jpg" class="profil frame"></div>
    <img src="../assets/spacer.png" id="spacer">
    <h3 class="beige bold">Øyvind Hellenes / Medhjelpar</h3>
    <div><img src="../assets/oyvind.jpg" class="profil frame"></div>
    <h4 class="beige p">
      Er utdanna programmerer og forretningsutvikler. Jobbar til dagleg med Protolab Vest i Førde.
      Har vore lidenskapleg oppteken av tennis heilt sidan han såg Roger Federer vinne Wimbledon i 2009.
      Meiner ei tennisbane er det Førde som by treng mest av alt dersom ein ser vekk i frå ein mini-replika av
      Hobbitun på Halbrendstølen og ein statue av Einar Førde med hest og kappe i rundkøyringa på Øyrane.
    </h4>
    <img src="../assets/spacer.png" id="spacer">
    <h3 class="beige bold">Kontakt</h3>
    <h4 class="beige p">
      EKontaktinfo: post@fordetennis.no eller 94055843.
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
.profil {
  width: 250px;
}

</style>
