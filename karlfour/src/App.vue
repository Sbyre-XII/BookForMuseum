<template>
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
