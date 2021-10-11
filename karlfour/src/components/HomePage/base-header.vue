<template>
    <header>
      <div class="page_top">
        <!--<button @click="GoHome()">Home</button>
        <button @click="GoShop()">Shop</button>
        <button @click="GoContact()">Contact</button>
        <button @click="GoBasket()">Basket</button>-->
      </div>
    </header>
</template>

<script>
import BasketPage from './BasketPage';
import ContactPage from './ContactPage';
import ShopPage from './ShopPage';

export default {
  name: 'base-header',
  components: {
    BasketPage,
    ContactPage,
    ShopPage
  },
  methods: {
    goHome(){
      location.replace("./components/HomePage/HomePage.vue")
    }
  }
}

function GoShop(){
  location.replace("./components/HomePage/ShopPage.vue")
}
function GoContact(){
  location.replace("./components/HomePage/ContactPage.vue")
}
function GoBasket(){
  location.replace("./components/HomePage/BasketPage.vue")
}

</script>

<style scoped>
.page_top {
  overflow: hidden;
  background-color: #333;
  position: fixed;
  top: 0;
  width: 100%;
}

.page_top a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

.page_top a:hover {
  background: #ddd;
  color: black;
}
</style>