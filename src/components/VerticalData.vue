<script setup>
import { defineProps } from 'vue'

const props = defineProps(['temp', 'icon', 'time',])
</script>

<template>
  <div class="flex flex-col items-center gap-2 pt-3">
    <span class="font-medium">{{ props.time }}</span>
    <i class="text-4xl" :class="props.icon"></i>
    <span class="text-lg">{{ props.temp }}<span class="text-sm align-top">°C</span></span>
  </div>
</template>