<template>
  <Heading />
  <Hero />
  <Promo />
  <Footer />
</template>

<script>
import Heading from './layouts/Heading.vue'
import Hero from './layouts/Hero.vue'
import Promo from './layouts/Promo.vue'
import Footer from './layouts/Footer.vue'

export default { components: { Heading, Hero, Promo, Footer } }
</script>

<style scoped></style>
