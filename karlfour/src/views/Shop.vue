// views/Shop.vue
<template>
    <base-header />
    <h1>ShopPage</h1>
    <BaseProduct title="Sabre laser" description="Les sabres lasers sont les armes des jedis" imageProduct="../components/img/Sabre.png" price="500" />
    <BaseProduct title="Hoverboard" description="Plus de soucis de transport, tracez vous même votre route" imageProduct="../components/img/Board.jpg" price="200" />
    <BaseProduct title="Portal gun" description="Placer deux portails pour vous rendre d’un point A à un point B, mais seulement sur une surface blanche" imageProduct="../components/img/Gun.jpg" price="450" />
    <BaseProduct title="Nimbus 2000" description="Ce n’est pas n’importe quel balai Harry, c’est un Nimbus 2000 !" imageProduct="../components/img/Nimbus.jpg" price="100" />
    <BaseProduct title="Pilule rouge" description="Prend la pilule rouge, et on reste dans le pays des merveilles et on descend avec le lapin blanc au fond du gouffre" imageProduct="../components/img/Pillule.jpg" price="700" />
    <BaseProduct title="Armure du chevalier pégase" description="Brûle ton cosmos, chevalier et atteint le 7e sens" imageProduct="../components/img/Armure.png" price="900" />
    <BaseProduct title="Flèche" description="Avec ça, obtenez un stand, une matérialisation psychique de votre esprit" imageProduct="../components/img/Flèche.png" price="400" />
    <BaseProduct title="Anneau unique" description="Avec ça, plus besoin de se prendre la tête pour reconquérir la terre du milieu" imageProduct="../components/img/Anneau.png" price="2000" />
    <BaseProduct title="La Batmobile" description="Je suis la vengeance, je suis la nuit, je suis un plagiat de Batman!" imageProduct="../components/img/BAT.jpg" price="4000" />
    <BaseProduct title="Diplôme d’ingénieur d’Efrei Paris (image non contractuel)" description="Vous pouvez payer en plusieur fois, 8000 par an pendant 5 ans et obtenez le prestigieux diplôme d’Efrei Paris" imageProduct="../components/img/Diplome.JPG" price="40000" />
    <base-footer />
</template>

<script>
import BaseFooter from '../components/BaseFooter.vue'
import BaseHeader from '../components/BaseHeader.vue'
import BaseProduct from '../components/BaseProduct.vue'
export default {
  components: { BaseProduct, BaseHeader, BaseFooter },
  name: 'ShopPage',
}
</script>