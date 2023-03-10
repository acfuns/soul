<script setup lang="ts">
const goods = [
  { id: 1, src: '/soft_toys_banners_0106c99a12.png' },
  { id: 2, src: '/books_banners_00ddf826ad.png' },
  { id: 3, src: '/vintage_banners_d01820f955.png' },
  { id: 4, src: '/vintage_banners_d01820f955.png' },
]
</script>

<template>
  <div class="grid grid-cols-3 gap-5 lt-md:grid-cols-1">
    <div v-for="it of goods" :key="it.id">
      <img class="rounded" :src="it.src" alt="" loading="lazy">
      <div class="mt-4 text-center">
        <h2 class="text-3xl font-semibold my-3">
          Soft Toys
        </h2>
        <p class="text-lg my-3">
          Children soft toys for all ages
        </p>
        <button class="btn text-lg my-4 transition duration-500">
          Shop Soft Toys
        </button>
      </div>
    </div>
    <!-- <div><img src="/books_banners_00ddf826ad.png" alt=""></div>
    <div><img src="/vintage_banners_d01820f955.png" alt=""></div> -->
  </div>
</template>
