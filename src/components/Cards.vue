<template>
 <fwb-card href="#">
  <fwb-img alt="flowbite-vue" src="src\assets\nike-1.jpg" />
  <div class="p-5 m-9">
   <h5 class="mb-2 text-xl font-bold tracking-tight text-gray-900 dark:text-white">Noteworthy technology acquisitions 2021</h5>
   <p class="font-normal text-gray-700 dark:text-gray-400">Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.</p>
  </div>
  <fwb-rating :rating="1" :scale="1" review-link="#" review-text="73 reviews">
   <template #besideText>
    <p class="ml-2 text-sm font-bold text-gray-900 dark:text-white">4.95</p>
   </template>
  </fwb-rating>
  <fwb-button :loading="loading" color="default" loading-position="suffix" outline @click="loading = !loading">
   Order Now
   <template #suffix>
    <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
     <path clip-rule="evenodd" d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z" fill-rule="evenodd" />
    </svg>
   </template>
  </fwb-button>
 </fwb-card>
 <fwb-card href="#">
  <fwb-img alt="flowbite-vue" src="src\assets\nike-2.jpg" />
  <div class="p-5 m-9">
   <h5 class="mb-2 text-xl font-bold tracking-tight text-gray-900 dark:text-white">Noteworthy technology acquisitions 2021</h5>
   <p class="font-normal text-gray-700 dark:text-gray-400">Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.</p>
  </div>
  <fwb-rating :rating="1" :scale="1" review-link="#" review-text="73 reviews">
   <template #besideText>
    <p class="ml-2 text-sm font-bold text-gray-900 dark:text-white">4.95</p>
   </template>
  </fwb-rating>
  <fwb-button :loading="loading" color="default" loading-position="suffix" outline @click="loading = !loading">
   Order Now
   <template #suffix>
    <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
     <path clip-rule="evenodd" d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z" fill-rule="evenodd" />
    </svg>
   </template>
  </fwb-button>
 </fwb-card>
 <fwb-card href="#">
  <fwb-img alt="flowbite-vue" src="src\assets\nike-1.jpg" />
  <div class="p-5 m-9">
   <h5 class="mb-2 text-xl font-bold tracking-tight text-gray-900 dark:text-white">Noteworthy technology acquisitions 2021</h5>
   <p class="font-normal text-gray-700 dark:text-gray-400">Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.</p>
  </div>
  <fwb-rating :rating="1" :scale="1" review-link="#" review-text="73 reviews">
   <template #besideText>
    <p class="ml-2 text-sm font-bold text-gray-900 dark:text-white">4.95</p>
   </template>
  </fwb-rating>
  <fwb-button :loading="loading" color="default" loading-position="suffix" outline @click="loading = !loading">
   Order Now
   <template #suffix>
    <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
     <path clip-rule="evenodd" d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z" fill-rule="evenodd" />
    </svg>
   </template>
  </fwb-button>
 </fwb-card>
 <fwb-card href="#">
  <fwb-img alt="flowbite-vue" src="src\assets\nike-4.jpg" />
  <div class="p-5 m-9">
   <h5 class="mb-2 text-xl font-bold tracking-tight text-gray-900 dark:text-white">Noteworthy technology acquisitions 2021</h5>
   <p class="font-normal text-gray-700 dark:text-gray-400">Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.</p>
  </div>
  <fwb-rating :rating="1" :scale="1" review-link="#" review-text="73 reviews">
   <template #besideText>
    <p class="ml-2 text-sm font-bold text-gray-900 dark:text-white">4.95</p>
   </template>
  </fwb-rating>
  <fwb-button :loading="loading" color="default" loading-position="suffix" outline @click="loading = !loading">
   Order Now
   <template #suffix>
    <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
     <path clip-rule="evenodd" d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z" fill-rule="evenodd" />
    </svg>
   </template>
  </fwb-button>
 </fwb-card>
</template>

<script setup>
import { FwbCard, FwbRating, FwbImg } from "flowbite-vue";
import { ref } from "vue";
import { FwbButton } from "flowbite-vue";

const loading = ref(false);
</script>
