<script setup lang="ts"></script>

<template>
  <ul>
    <li>
      <NuxtLink to="/with-google-fonts">With Google Fonts</NuxtLink>
    </li>
    <li>
      <NuxtLink to="/with-modern-font-stacks">
        With Modern Font Stacks
      </NuxtLink>
    </li>
    <li>
      <NuxtLink to="/font-display-block">font-display: block</NuxtLink>
    </li>
    <li>
      <NuxtLink to="/font-display-swap">font-display: swap</NuxtLink>
    </li>
    <li>
      <NuxtLink to="/font-display-fallback"> font-display: fallback </NuxtLink>
    </li>
    <li>
      <NuxtLink to="/font-display-optional"> font-display: optional </NuxtLink>
    </li>
  </ul>
</template>

<style scoped>
ul {
  list-style: none;
  padding: 0;
  margin: 0;
}
a {
  font-size: 1.5rem;
  line-height: 1.5;
}
</style>
