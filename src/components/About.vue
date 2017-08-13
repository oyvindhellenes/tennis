<template>
  <div>
    <br>
    <h1 class="beige bold" id="title">Kven er vi?</h1>
    <br>
    <div><img src="../assets/team.jpg" class="full-width frame"></div>
    <h3 class="beige bold">Bård Nygaard Åsnes / Leiar</h3>
    <br>
    <div><img src="../assets/baard.jpg" class="profil frame"></div>
    <br>
    <h4 class="beige p">
      Er fjellmann og ivrig mosjonist. Blei interessert i tennis då han oppdaga ei tennisbane på parkeringsplassen
      til Scania som born. Var stor fan av Ivan Lendl på åttitalet. Har spelt fotball i alle år, men har tru på at tennis
      er ein bedre idrett å halde på med dei neste førti åra. Jobbar til dagleg med vaksenopplæring på Førde norsksenter.
    </h4>
    <img src="../assets/spacer.png" id="spacer">
    <h3 class="beige bold">Anders Thommessen / Nestleiar</h3>
    <br>
    <div><img src="../assets/anders.jpg" class="profil frame"></div>
    <br>
    <h4 class="beige p">
      Far til 3 små og jobber som lege på øyeavdelinga FSS. Vokste opp i Lørenskog, og har spilt tennis fra 6 års alder.
      Bodd drøye 5 år i Førde og savner tennis sårt. Har stort engasjement for barneidrett, og har jobbet i mange år som tennistrener.
      Har trenerkurs i generell barneidrett, og har tennistrenerkurs på nest høyeste nivå i Norge.
      Jeg har lyst til å komme igang igjen med trenergjerningen. Har veldig lyst til å skape et alternativ til fotball, volleyball
      og håndball i Førde. Tennis passer for alle og i alle aldre.
    </h4>
    <img src="../assets/spacer.png" id="spacer">
    <h3 class="beige bold">Martin Savland / Styremedlem</h3>
    <br>
    <div><img src="../assets/martin.jpg" class="profil frame"></div>
    <br>
    <h4 class="beige p">
      27 år og busatt i Naustdal, jobbar i Førde og utdanna siviløkonom. Aktiv i Høgre. Eg ynskjer tennisbane i Førde
      slik at eg kan spele tennis etter ein hard arbeidsdag. Eg vil gjerne også få muligheiten til å bli kjent med andre
      tennisinteresserte sunnfjordringar.
    </h4>
    <img src="../assets/spacer.png" id="spacer">
    <h3 class="beige bold">Øyvind Hellenes / Medhjelpar</h3>
    <br>
    <div><img src="../assets/oyvind.jpg" class="profil frame"></div>
    <br>
    <h4 class="beige p">
      Er utdanna programmerar og forretningsutviklar. Jobbar til dagleg med Protolab Vest i Førde.
      Har vore lidenskapleg oppteken av tennis heilt sidan han såg Roger Federer vinne Wimbledon i 2009.
      Meiner ei tennisbane er det Førde som by treng mest av alt dersom ein ser vekk i frå ein mini-replika av
      Hobbitun på Halbrendstølen og ein statue av Einar Førde med hest og kappe i rundkøyringa på Øyrane.
    </h4>
    <img src="../assets/spacer.png" id="spacer">
    <h2 class="beige bold">Kontaktinfo</h2>
    <br>
    <h4 class="beige p">
      Epost: <a href="bardasnes@outlook.com"><span class="bold-underscore"> bardasnes@outlook.com</span></a>
    </h4>
    <h4 class="beige p">
      Telefon: <span class="bold-underscore"> 918 81 992</span>
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
