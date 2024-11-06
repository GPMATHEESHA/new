<script lang="ts" setup>
// https://github.com/vueuse/head
// you can use this to manipulate the document head in any components,
// they will be rendered correctly in the html results with vite-ssg
useHead({
  title: 'Retirement',
  meta: [{ name: 'description', content: 'Happy Retirement Life Sir!' }],
})
</script>

<template>
  <router-view />
</template>
