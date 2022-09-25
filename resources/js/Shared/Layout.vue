<template>
  <section class="p-6 bg-gray-200">
    <header class="flex justify-between">
      <h1 class="font-bold text-lg">Laravel with Vue</h1>
      <Nav />
    </header>
  </section>
  <section class="p-6">
    <slot />
  </section>
</template>

<script>
import Nav from "./Nav.vue";

export default {
  components: {
    Nav,
  },
};
</script>

<style>
</style>