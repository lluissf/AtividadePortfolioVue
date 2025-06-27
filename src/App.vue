<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HeaderPortfolio from './components/Header.vue'
import FooterPortfolio from './components/Footer.vue'
</script>
<template>

  <body>
    <HeaderPortfolio />
    <main>
      <RouterView />
    </main>
    <FooterPortfolio />
  </body>
</template>