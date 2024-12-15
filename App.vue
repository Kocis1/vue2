<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/gallery">Gallery</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>
  nav
  {
    text-align: center;
  }
  nav *
  {
    border: solid 1px black;
    background-color: aquamarine;
  }
</style>
