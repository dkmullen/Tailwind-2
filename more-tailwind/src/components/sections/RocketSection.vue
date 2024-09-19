<script setup>
import RocketListItem from './subsections/RocketListItem.vue'

const rockets = [
  {
    name: 'Explorer',
    image: '/src/assets/img/rocketman.png',
    price: '$',
    description: 'Affordable Exploration'
  },
  {
    name: 'Adventurer',
    image: '/src/assets/img/rocketride.png',
    price: '$$',
    description: 'Best Selling Rocket'
  },
  {
    name: 'Infinity',
    image: '/src/assets/img/rocketlaunch.png',
    price: '$$$',
    description: 'Luxury Starship'
  }
]
</script>

<template>
  <section id="rockets" class="p-6 my-12 scroll-mt-20">
    <h2 class="text-4xl font-bold text-center sm:text-5xl mb-6 text-slate-900 dark:text-white">
      Our Rockets
    </h2>
    <ul class="list-none mx-auto my-12 flex flex-col sm:flex-row items-center gap-8">
      <RocketListItem
        v-for="i in rockets"
        :key="i.name"
        :name="i.name"
        :image="i.image"
        :price="i.price"
        :description="i.description"
      />
    </ul>
  </section>
</template>
