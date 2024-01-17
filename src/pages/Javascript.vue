<script setup>
import Card from '../components/Card.vue';
</script>

<template>
  <div class="page">
    <h1>Javascript</h1>
    <Card />
  </div>
</template>

<style lang="scss" scoped>
h1 {
  font-size: 3rem;
  font-weight: 800;
}
.page {
  height: 100svh;
  width: 100svw;
  background-color: #f4d04e;

  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;

  gap: 3rem;
}
</style>
