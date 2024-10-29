<script setup lang="ts">

</script>
<!-- http://localhost:3000/members/admin/samit -->
<template>
    <div>
        <h1>Member Page</h1>
        <p>Group: {{ $route.params.group }}</p>
        <p>Member: {{ $route.params.id }}</p>
    </div>
</template>

<style scoped>

</style>