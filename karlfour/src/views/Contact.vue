// views/Contact.vue
<template>
  <base-header />
  <h1>ContactPage</h1>
  <base-footer />
</template>

<script>
import BaseFooter from '../components/BaseFooter.vue'
import BaseHeader from '../components/BaseHeader.vue'
export default {
  components: { BaseHeader, BaseFooter },
  name: 'ContactPage',
}
</script>