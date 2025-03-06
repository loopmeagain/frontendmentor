<script setup lang="ts">
import { RouterLink } from 'vue-router'
import Cart from '@/components/Cart.vue'
import IconLogo from '@/components/icons/IconLogo.vue'
import Avatar from '@/components/Avatar.vue'
</script>

<template>
  <header>
    <RouterLink to="/">
      <IconLogo/>
    </RouterLink>
    <nav>
      <RouterLink to="/collections">Collections</RouterLink>
      <RouterLink to="/women">Men</RouterLink>
      <RouterLink to="/women">Women</RouterLink>
      <RouterLink to="/about">About</RouterLink>
      <RouterLink to="/contact">Contact</RouterLink>
    </nav>
    <Cart/>
    <Avatar/>
  </header>

  <RouterView />
</template>

<style scoped>
header {
  min-width: 70rem;
  display: flex;
  justify-content: center;
  align-items: center;
  border-bottom: 1px solid hsl(0, 0%, 90%);
  padding-bottom: 2.2rem;
}
nav a {
  display: inline-block;
  padding: 0 1rem;
  color: hsl(0, 0%, 0%);
}
nav a:hover {
  outline: 4px solid hsl(26, 100%, 55%);
  outline-offset: 2.8rem;
  clip-path: inset(0 18% -3rem 15%);
}

nav a:first-of-type {
  margin-left: 2.5rem;
}
nav a:last-of-type {
  margin-right: 24rem;
}
header img:last-of-type {
  margin-left: 3rem;
}
</style>
