<template>
  <h1>Welcome</h1>
  This page is:
  <ul>
    <li>Rendered to HTML.</li>
    <li>Interactive. <Counter /></li>
  </ul>
</template>

<script lang="ts">
export const documentProps = {
  // This title and description will override the defaults
  title: 'About SpaceX',
  description: 'Our mission is to explore the galaxy.',
  image: 'https://vista.today/wp-content/uploads/2022/08/The-Road-to-Success-1-970x550.jpg'
}
</script>
<script lang="ts" setup>
import Counter from './Counter.vue'
</script>
