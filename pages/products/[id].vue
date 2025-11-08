<template>
    <div>
        <p>Product details for {{ id }}</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Culpa cumque minima molestias porro quisquam nostrum ea, veritatis aspernatur magnam repudiandae ad! Minus officiis magni neque quod eos explicabo dolores repudiandae?</p>
    </div>
</template>

<script setup>
    const { id } = useRoute().params
</script>

<style scoped>

</style>