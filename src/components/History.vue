<script setup>
import StatCounter from './StatCounter.vue'

const stats = [
  { value: 106, label: 'Businesses', suffix: '' },
  { value: 8, label: 'Countries', suffix: '' },
  { value: 60, label: 'Projects', suffix: '+' },
  { value: 4, label: 'Years Experience', suffix: 'M+' },
]
</script>

<template>
  <div class="mx-auto px-4 py-20 bg-cover bg-center" style="background-image: url('https://cdn.prod.website-files.com/6898ab1ec18a9c82d7d3ef50/689a48b60ea705a8fc3bbcae_Success%20Rate%20BG.avif');">
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
      <StatCounter 
        v-for="stat in stats" 
        :key="stat.label"
        :target-value="stat.value"
        :label="stat.label"
        :suffix="stat.suffix"
      />
    </div>
  </div>
</template>