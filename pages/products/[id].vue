<template>
    <div>
        <p>Product Details for {{ id }}</p>
        
    </div>
</template>

<script setup>
/*global useRoute, definePageMeta*/
const { id } = useRoute().params
definePageMeta({
        layout : 'products'
    })

</script>

<style lang="scss" scoped>

</style>