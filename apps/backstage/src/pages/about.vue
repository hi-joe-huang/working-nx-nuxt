<script setup lang="ts">
const foo = ref('b')
</script>
<template>
  <div class="about">
    {{ foo }}
    <h1>This is an about page.</h1>
  </div>
</template>

<style>
@media (min-width: 768px) {
  .about {
    max-width: 768px;
    margin-left: auto;
    margin-right: auto;
    padding: 0 1rem;
  }
}
</style>
