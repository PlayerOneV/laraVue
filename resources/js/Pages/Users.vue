<template>
  <h1 class="text-3xl font-bold">Users</h1>

  <div style="margin-top: 400px">
    <p>The current time is {{ time }}.</p>
  </div>

  <Link href="/users" class="text-blue-500" preserve-scroll>Refresh</Link>
</template>

<script>
import Layout from "../Shared/Layout.vue";

export default {
  layout: Layout,
  components: {},
  props: {
    time: String,
  },
};
</script>

