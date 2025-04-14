<template>
  <div>
    <Nav />
    <div class="p-6">
      <RouterView />
    </div>
  </div>
</template>

<script setup lang="ts">
import Nav from './components/Nav.vue';

</script>