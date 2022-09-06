<script setup>
import appSide from './appSide.vue'
import appSection from './appSection.vue'
</script>

<template>
  <div class="app-content">
    <appSide></appSide>
    <appSection></appSection>
  </div>
</template>

<style scoped lang="scss">
.app-content {
  display: flex;
  height: 100%;
  overflow: hidden;
  padding: 16px 24px 24px 0;
  // background-color: brown;
}
</style>
