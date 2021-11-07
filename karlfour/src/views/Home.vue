<template>
    <base-header />
    <h1>Bienvenue chez Karlfour !</h1>
    <h2>Une boutique créée pour répondre aux besoins de nos clients.</h2>
    <div>
        <br>
        <figcaption> Ce site est un projet web à réaliser pour l école. Il a pour </figcaption>
        <figcaption> but de proposer des produits que le client peut consuleter et</figcaption>
        <figcaption> les mettre dans leur panier. Karlfour esst justement là pour</figcaption>
        <figcaption> ça. Il propose des produit atypique qui peuvent séduire tout</figcaption>
        <figcaption> type de client. </figcaption>
    <br>
    <p><b>Réalisé par</b> : Josselin RENAN et Martin RATTANAVAN</p>
</div>
    <base-footer />
</template>

<script>
import BaseFooter from '../components/BaseFooter.vue'
import BaseHeader from '../components/BaseHeader.vue'
export default {
  components: { BaseHeader, BaseFooter },
  name: 'HomePage',
}
</script>



