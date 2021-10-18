<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/shop">Shop</router-link>
    <router-link to="/contact">Contact</router-link>
    <router-link to="/basket">Basket</router-link>
  </div>
  <router-view/>  
    <base-layout>
      <HomePage />
    </base-layout>
</template>

<script>

import HomePage from './components/pages/home-page.vue'
import BaseLayout from './components/base-layout.vue'

export default {
  name: 'App',
  components: {
    HomePage,
    BaseLayout
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
