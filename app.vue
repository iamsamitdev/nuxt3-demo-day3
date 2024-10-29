<script setup lang="ts">
  import '~/assets/css/app.css'
</script>
<template>

  <main>
    <div class="menu">
      <ul>
        <li>
          <NuxtLink to="/">/</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/about">/about</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/contact">/contact</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/users/samit?type=admin&page=1">/users/samit?type=admin&page=1</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/members/admin/samit">/members/admin/samit</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/category/programming">/category/programming</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/parent/child">/parent/child</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/parent/sister">/parent/sister</NuxtLink>
        </li>
      </ul>
    </div>
    <div class="content">
      <NuxtPage />
    </div>
  </main>
  
</template>
