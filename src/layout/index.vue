<script setup>
import appheader from './components/header.vue'
import content from './components/content.vue'
</script>

<template>
  <div class="app-container">
    <appheader></appheader>
    <content></content>
  </div>
</template>

<style scoped lang="scss">
@import '../style.css';
.app-container {
  width: 100%;
  height: 100vh;
  display: flex;
  flex-direction: column;
  background-color: var(--app-container);
  // background-color: blueviolet;
  transition: 0.2s;
  max-width: 1800px;

  button,
  input,
  optgroup,
  select,
  textarea {
    font-family: 'DM Sans', sans-serif;
  }
}
</style>
