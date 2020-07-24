<template>
    <div>
        <router-link to="/admin/product-add">Creation d'un nouveau livre</router-link>
        <ProductList />
    </div>
</template>

<script>
    import ProductList from "@/components/admin/ProductList";
    export default {
        name: "Products",
        components: {
            ProductList,
        }
    }
</script>

<style scoped>

</style>