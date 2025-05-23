<template>
  <section class="grid">
    <LayoutSideBar/>
    <div>
      <slot/>
    </div>
  </section>
</template>

<script setup lang="ts">

</script>

<style scoped>
  .grid {
    min-height: 100vh;
    grid-template-columns: 1fr 6fr;
    display: grid;
  }
</style>