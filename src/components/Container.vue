<script setup>
import Status from './Status.vue'
import DetailsWrapper from './DetailsWrapper.vue'
</script>

<template>
  <div class="flex justify-between items-start flex-col lg:flex-row text-white mt-10">
    <!-- Container -->
    <div class="p-3 basis-1/2 self-end">
      <Status />
    </div>
    <div class="p-3 basis-1/2">
      <DetailsWrapper />
    </div>
  </div>
</template>