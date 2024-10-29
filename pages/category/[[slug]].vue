<script setup lang="ts"></script>

<template>
  <div>
    <h1>Category Slug Page</h1>
    <p v-if="$route.params.slug">Category: {{ $route.params.slug }}</p>
    <p v-else>Not found category</p>
  </div>
</template>

<style scoped></style>
