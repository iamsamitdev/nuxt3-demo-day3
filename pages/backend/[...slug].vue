<script setup lang="ts">

  const route = useRoute()
  const slug = ref(route.params.slug)
  console.log(slug)

</script>

<template>
  <div>
    <h1>Backend Page</h1>
    <p v-if="$route.params.slug">Backend: {{ $route.params.slug }}</p>
    <!-- Loop parameter -->
    <ul>
      <li v-for="item in slug" :key="item">{{ item }}</li>
    </ul>
  </div>
</template>

<style scoped></style>
