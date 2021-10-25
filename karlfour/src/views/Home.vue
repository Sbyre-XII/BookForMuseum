<template>
  <h1>Bienvenue chez Karlfour !</h1>
  <h2>Une boutique créée pour répondre aux besoins de nos clients.</h2>
  <base-product title="M16" description="Fusil d'assault" imageProduct="../components/img/chat.jpg" price="499" />
  <base-product title="M16" description="Fusil d'assault" imageProduct="../components/img/chat.jpg" price="200" />
</template>

<script>
import baseProduct from '../components/base-product.vue'
export default {
  components: { baseProduct },
  name: 'HomePage',
}
</script>

