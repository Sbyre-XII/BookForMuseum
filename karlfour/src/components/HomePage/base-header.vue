<template>
    <header>
      <div class="page_top">
        <a href="#home">Home</a>
        <a href="#news">Shop</a>
        <a href="#contact">Contact</a>
        <a href="#basket">Basket</a>
      </div>
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