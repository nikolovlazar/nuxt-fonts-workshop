<script setup lang="ts"></script>

<template>
  <ul>
    <li>
      <router-link to="/with-google-fonts">With Google Fonts</router-link>
    </li>
    <li>
      <router-link to="/with-modern-font-stacks">
        With Modern Font Stacks
      </router-link>
    </li>
    <li>
      <router-link to="/font-display-block">font-display: block</router-link>
    </li>
    <li>
      <router-link to="/font-display-swap">font-display: swap</router-link>
    </li>
    <li>
      <router-link to="/font-display-fallback">
        font-display: fallback
      </router-link>
    </li>
    <li>
      <router-link to="/font-display-optional">
        font-display: optional
      </router-link>
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
