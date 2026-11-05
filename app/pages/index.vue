<template>
  <div class="container">
    <h1>My DevOps Project</h1>
    <p>Welcome to Nuxt 4</p>
    <button @click="count++">
      Click: {{ count }}
    </button>
  </div>
</template>

<script setup>
const count = ref(0)
</script>
