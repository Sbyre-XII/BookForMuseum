<template>
  <base-header />
  <h1>Bienvenue chez Karlfour !</h1>
  <h2>Une boutique créée pour répondre aux besoins de nos clients.</h2>
  <BaseProduct title="M16" description="Fusil d'assault" imageProduct="../components/img/chat.jpg" price="499" />
  <BaseProduct title="M16" description="Fusil d'assault" imageProduct="../components/img/chat.jpg" price="200" />
  <base-footer />
</template>

<script>
import BaseFooter from '../components/BaseFooter.vue'
import BaseHeader from '../components/BaseHeader.vue'
import BaseProduct from '../components/BaseProduct.vue'
export default {
  components: { BaseProduct, BaseHeader, BaseFooter },
  name: 'HomePage',
}
</script>

