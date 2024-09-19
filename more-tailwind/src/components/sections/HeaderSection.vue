<script setup>
const menuItems = [
  { name: 'Our Rockets', href: '#rockets' },
  { name: 'Testimonials', href: '#testimonials' },
  { name: 'Contact Us', href: '#contact' }
]
</script>
<template>
  <header class="bg-teal-700 text-white sticky top-0 z-10">
    <section class="max-w-4xl mx-auto p-4 flex justify-between items-center">
      <h1 class="text-3xl font-medium">
        <a href="#hero">🚀 ACME Rockets</a>
      </h1>
      <div>
        <button id="mobile-open-button" class="text-3xl sm:hidden focus:outline-none">
          &#9776;
        </button>
        <nav class="hidden sm:block space-x-8 text-xl" aria-label="main">
          <a :href="i.href" class="hover:opacity-90" v-for="i in menuItems" :key="i.name">{{
            i.name
          }}</a>
        </nav>
      </div>
    </section>
  </header>
</template>
