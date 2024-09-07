<template>
  <div id="app-view">
    <!-- <NavigationBar /> -->
    <RouterView />
  </div>
</template>

<script setup>
import NavigationBar from '@/components/common/NavigationBar.vue'
import { RouterView } from 'vue-router'
</script>

<style scoped></style>
