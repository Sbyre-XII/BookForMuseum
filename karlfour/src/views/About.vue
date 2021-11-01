<template>
  <base-header />
  <div class="about">
    <h1>This is an about page</h1>
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