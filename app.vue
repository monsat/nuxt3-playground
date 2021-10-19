<script setup lang="ts">
console.log('app.vue')
onMounted(() => { console.log('app.vue', 'mounted') })
</script>

<template>
  <div id="app-vue">
    <NuxtPage/>
  </div>
</template>
