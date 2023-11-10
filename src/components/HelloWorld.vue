<script setup lang="ts">

defineProps<{ msg: string }>()

</script>

<template>
    <h1>{{ msg }}</h1>
    <p>componente editado</p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
