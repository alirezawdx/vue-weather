<script setup>
import VerticalData from './VerticalData.vue'
</script>

<template>
  <div class="">
    <div class="text-white bg-black p-8 rounded-2xl bg-opacity-20 backdrop-blur-sm text-sm">
      Thunderstorms expected around 00:00
      <hr class="mt-3 opacity-50">
      <div class="flex flex-row justify-between">
        <VerticalData temp="24" icon="ri-sun-fill" time="Now" />
        <VerticalData temp="22" icon="ri-sun-foggy-fill" time="00" />
        <VerticalData temp="14" icon="ri-sun-cloudy-fill" time="01" />
        <VerticalData temp="15" icon="ri-windy-fill" time="02" />
        <VerticalData temp="17" icon="ri-snowy-fill" time="03" />
        <VerticalData temp="12" icon="ri-moon-cloudy-fill" time="04" />
        <VerticalData temp="16" icon="ri-showers-fill" time="05" />
      </div>
    </div>
    <div class="text-white bg-black p-8 rounded-2xl bg-opacity-20 backdrop-blur-sm text-sm mt-6">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ad, aliquam eligendi ut incidunt excepturi sapiente nostrum exercitationem eaque dolorum omnis modi, sint eum corporis. Quasi delectus pariatur veritatis accusamus optio. Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae saepe laborum sit veritatis aspernatur rerum dolor recusandae debitis nihil minus, deserunt, in, provident iure odio ab optio sed! Nisi, et. Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam dolores, ratione ut exercitationem ullam optio incidunt fuga eveniet reprehenderit id, ipsum architecto et provident, dolorem repellendus aut non labore eius?</div>
  </div>
</template>