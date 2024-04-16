<script setup>
import Cards from "./cards.vue";
import Head from "./head.vue";
import Footers from "./footers.vue";
</script>

<template>
 <div>
  <header>
   <Head />
  </header>
 </div>
 <div class="font-mono text-red-300 text-3xl">New Arrivals</div>
 <div class="flex">
  <Cards />
 </div>
 <div>
  <Footers />
 </div>
</template>
