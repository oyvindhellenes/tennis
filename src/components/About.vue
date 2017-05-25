<template>
  <div>
      <h1 class="beige bold" id="title">Om oss</h1>

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



</style>
