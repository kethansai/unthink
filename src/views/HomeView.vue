<template>
  <div id="home-view">
    <img :src="logo" alt="unthink" class="logo" />
  </div>
</template>
<script setup>
import logo from '@/assets/images/logo.svg'
</script>
<style scoped lang="scss">
#home-view {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-color: black;
  img {
    height: 100vh;
  }
}
</style>
