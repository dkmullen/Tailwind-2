<script setup></script>

<template>
  <section
    id="hero"
    class="flex flex-col-reverse justify-center sm:flex-row p-6 items-center gap-8 mb-12 scroll-mt-40"
  >
    <article class="sm:w-1/2">
      <h2
        class="max-w-md text-4xl font-bold text-center sm:text-5xl sm:text-left text-slate-900 dark:text-white"
      >
        We boldly go
        <span class="text-indigo-700 dark:text-indigp-300">where no rocket</span>
        has gone before...
      </h2>
      <p class="max-w-md text-2xl mt-4 text-center sm:text-left text-slate-700 dark:text-slate-400">
        We're building rockets for the next century today! From the moon to Mars, Jupiter, and
        beyond, we're here to help you get there.
      </p>
      <p class="max-w-md text-2xl mt-4 text-center sm:text-left text-slate-700 dark:text-slate-400">
        Think ACME Rockets
      </p>
    </article>
    <img class="w-1/2" src="@/assets/img/rocketdab.png" alt="Rocket Dab" />
  </section>
</template>
