<script setup>
import { ref, onMounted } from 'vue'
import { useTransition, TransitionPresets, useIntersectionObserver } from '@vueuse/core'

const props = defineProps({
  targetValue: { type: Number, required: true },
  label: { type: String, required: true },
  suffix: { type: String, default: '' }
})

const source = ref(0)
const target = ref(null) 

const output = useTransition(source, {
  duration: 2500,
  transition: TransitionPresets.easeOutExpo,
})

const { stop } = useIntersectionObserver(
  target,
  ([{ isIntersecting }]) => {
    if (isIntersecting) {
      source.value = props.targetValue
      stop()
    }
  },
  { threshold: 0.5 }
)
</script>

<template>
  <div ref="target" class="flex flex-col items-center p-6 ">
    <span class="text-5xl font-extrabold text-black-600 tracking-tight tabular-nums">
      {{ Math.round(output) }}{{ suffix }}
    </span>
    <p class="mt-2 text-gray-500 font-medium uppercase text-sm tracking-widest">
      {{ label }}
    </p>
  </div>
</template>