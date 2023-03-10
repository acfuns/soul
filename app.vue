<script setup lang="ts">
useHead({
  title: '母婴产品商城',
  link: [
    {
      rel: 'icon', type: 'image/png', href: '/nuxt.png',
    },
  ],
})
</script>

<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>

<style>
html, body , #__nuxt{
  height: 200vh;
  margin: 0;
  padding: 0;
}

html.dark {
  --tw-bg-opacity: 1;
  background-color: rgb(12 12 13/var(--tw-bg-opacity));
  color: white;
}
</style>
