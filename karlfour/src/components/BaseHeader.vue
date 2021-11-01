<template>
    <header>
      <div class="page_top">
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link> |
        <router-link to="/card">Card</router-link> |
        <router-link to="/shop">Shop</router-link> |
        <router-link to="/contact">Contact</router-link>
      </div>
      <router-view/>
    </header>
</template>

<script>
export default {
  name: 'base-header',
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