<template>
  <AppHeader />
  <main>
    <RouterView />
  </main>
  <AppFooter />
</template>

<script setup>
import AppHeader from '../global/AppHeader.vue'
import AppFooter from '../global/AppFooter.vue'
</script>
