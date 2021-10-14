<template>
  <h1>Bienvenue chez Karlfour !</h1>
  <h2>Une boutique créée pour répondre aux besoins de nos clients.</h2>
  <base-product title="M16" description="Fusil d'assault" imageProduct="https://previews.123rf.com/images/yanas/yanas1505/yanas150500003/40002833-dessin-anim%C3%A9-pingouin.jpg" price="499" />
  <base-product title="M16" description="Fusil d'assault" imageProduct="https://previews.123rf.com/images/yanas/yanas1505/yanas150500003/40002833-dessin-anim%C3%A9-pingouin.jpg" price="200" />
</template>

<script>
import baseProduct from '../base-product.vue'
export default {
  components: { baseProduct },
  name: 'HomePage',
}
</script>