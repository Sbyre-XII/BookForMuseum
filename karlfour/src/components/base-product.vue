<template>
    <div id="product">
        <h2>{{title}}</h2>
        <h3>{{description}}</h3>
        <h3>{{price}}</h3>
        <img class="imgProduct" :src="imageProduct" /> 
    </div>
</template>

<script>
export default{
    name: "base-product",
    components: {},
    props: {
        title: String,
        price: Int32Array,
        description: String,
        imageProduct: String
    }
}
</script>

<style scoped>
.imgProduct{
    border: 1px solid #ddd;
    border-radius: 4px;
    padding: 5px;
    width: 150px;
}
</style>
