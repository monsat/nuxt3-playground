<script setup lang="ts">
console.log('layouts/default.vue')
onMounted(() => { console.log('layout', 'mounted') })
</script>

<template>
  <div id="layout-default-vue">
    <slot/>
  </div>
</template>
