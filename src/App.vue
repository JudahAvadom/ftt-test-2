<template>
  <div id="app">
    <Navbar />
    <Promo />
  </div>
</template>

<script>

import Navbar from './components/Navbar.vue';
import Promo from './components/Promo.vue';

export default {
  name: 'App',
  components: {
    Navbar,
    Promo
  }
}
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Nanum+Gothic:wght@400;700;800&display=swap');

  * {
    padding: 0;
    margin: 0;
    font-family: 'Nanum Gothic', sans-serif;
  }

  ul, ol {
    list-style: none;
  }
</style>
