<script setup>
    const route = useRoute()
    const id = route.params.id
</script>
<template>
    <p>id = {{ id }}</p>
</template>