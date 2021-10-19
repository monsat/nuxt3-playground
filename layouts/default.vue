<script setup lang="ts">
console.log('layouts/default.vue')
onMounted(() => { console.log('layout', 'mounted') })
</script>

<template>
  <div>
    <slot/>
  </div>
</template>
