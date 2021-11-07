// views/Contact.vue
<template>
    <base-header />
    <h1>ContactPage</h1>
    <h2>Notre but est de proposer une selection de produit qui peuvent potentiellement interreser ceux qui passe voir ce site</h2>

    <div>


        <img src="/components/img/Josselin.jpg" />
        <figcaption>Josselin RENAN</figcaption>
        <figcaption>renan.josselin@efrei.net</figcaption>
        <br />
        <img src="/components/img/Martin.JPG" />
        <figcaption>Martin Rattanavan</figcaption>
        <figcaption>rattanavan.martin@efrei.net</figcaption>

    </div>
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