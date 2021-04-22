<template>
  <div>
    <h1>Novosti</h1>

    <moja-kartica naslov="Prva novost" tekst="U VueJS sve gledamo kao komponetu." />
    <moja-kartica naslov="Druga novost" tekst="Ovdje smo iskoritili opet MojuKarticu." />
    <moja-kartica naslov="Treća novost" tekst="I to je to. :)" />
  </div>
</template>

<script>
import MojaKartica from '../components/MojaKartica.vue'

export default {
  name: 'Profile',
  components: {
    MojaKartica
  }
}
</script>
