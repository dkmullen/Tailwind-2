<script setup>
defineProps(['name', 'image', 'price', 'description'])
</script>

<template>
  <li
    class="w-2/3 sm:w-5/6 flex flex-col items-center border border-solid corder-slate-900 dark:border-gray-100 bg-white dark:bg-black py-6 px-2 rounded-3xl shadow-xl"
  >
    <img :src="image" :alt="name" class="mb-6 w-1/2" />
    <h3 class="text-3xl text-center text-slate-900 dark:text-white">{{ name }}</h3>

    <p class="hidden sm:block text-3xl mt-2 text-center text-slate-500 dark:text-slate-400">
      {{ price }}
    </p>
    <p class="sm:hidden text-2xl mt-2 text-center text-slate-500 dark:text-slate-400">
      {{ description }}
    </p>
  </li>
</template>
