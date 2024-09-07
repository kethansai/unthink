<template>
  <header>
    <div class="wrapper">
      <nav>
        <router-link to="/" exact>Home</router-link>
        <router-link to="/about">About</router-link>
      </nav>
    </div>
  </header>
</template>
<script setup>
import { RouterLink } from 'vue-router'
</script>
<style scoped lang="scss"></style>
