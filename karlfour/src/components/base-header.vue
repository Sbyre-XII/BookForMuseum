<template>
    <header>
      <div class="page_top">
        <a href="#home">Home</a>
        <a href="#news">Shop</a>
        <a href="#contact">Contact</a>
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
  position: fixed; /* Set the navbar to fixed position */
  top: 0; /* Position the navbar at the top of the page */
  width: 100%; /* Full width */
}

/* Links inside the navbar */
.page_top a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

/* Change background on mouse-over */
.page_top a:hover {
  background: #ddd;
  color: black;
}
</style>