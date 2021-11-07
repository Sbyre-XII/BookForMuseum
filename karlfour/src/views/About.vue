<template>
  <base-header />
  <div class="about">
    <h1>Nos partenaires</h1>
    <h2>Ce projet est en collaboration avec de nombreux investisseurs venu de toute les régions du monde ou même d'autre univers.</h2>
  </div>
  <base-footer />
</template>

<script>
import BaseFooter from '../components/BaseFooter.vue'
import BaseHeader from '../components/BaseHeader.vue'
export default {
  components: { BaseHeader, BaseFooter },
  name: 'AboutPage',
}
</script>