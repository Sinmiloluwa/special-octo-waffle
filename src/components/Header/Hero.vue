<script setup>
import BlueTextBody from '../BlueTextBody.vue';
</script>

<template>
    <section class="pt-16">
        <div class="flex items-start">
            <BlueTextBody>
                <span class="text-xl uppercase">Simply a studio_</span>
            </BlueTextBody>
        </div>
        <div class="flex justify-between py-8">
            <h2 class="text-7xl text-black font-black mb-4">Design strategy built<br> for startups on the rise.</h2>
            <div class="flex flex-col justify-end">
                <div class="flex justify-between gap-2">
                    <p class="text-orange-600">2019 - 25</p>
                    <div class="h-6 w-px bg-orange-600 mx-4"></div>
                    <p class="text-black uppercase text-lg font-bold">Featured Works_</p>
                </div>
            </div>
        </div>
        <div class="overflow-hidden py-8">
            <div class="flex gap-4 auto-scroll">
                <div class="flex-shrink-0">
                    <img src="https://images.unsplash.com/photo-1767449985562-013c41bd7fda?q=80&w=1035&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" class="w-80 h-100 bg-gray-300 rounded"></img>
                    <p class="mt-2 text-center text-black font-semibold">Project One</p>
                </div>
                <div class="flex-shrink-0">
                    <img src="https://images.unsplash.com/photo-1764649841485-82d7bd92760a?q=80&w=987&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" class="w-80 h-100 bg-gray-300 rounded"></img>
                    <p class="mt-2 text-center text-black font-semibold">Project Two</p>
                </div>
                <div class="flex-shrink-0">
                    <img src="https://images.unsplash.com/photo-1765004775664-24306ca36b8f?w=900&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxmZWF0dXJlZC1waG90b3MtZmVlZHwxNHx8fGVufDB8fHx8fA%3D%3D" class="w-80 h-100 bg-gray-300 rounded"></img>
                    <p class="mt-2 text-center text-black font-semibold">Project Three</p>
                </div>
                <div class="flex-shrink-0">
                    <img src="https://images.unsplash.com/photo-1764966894769-4b2944571d12?q=80&w=1065&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" class="w-80 h-100 bg-gray-300 rounded"></img>
                    <p class="mt-2 text-center text-black font-semibold">Project Four</p>
                </div>
                <div class="flex-shrink-0">
                    <img src="https://images.unsplash.com/photo-1765834082477-5f9c1466a7c4?w=900&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxmZWF0dXJlZC1waG90b3MtZmVlZHwyMXx8fGVufDB8fHx8fA%3D%3D" class="w-80 h-100 bg-gray-300 rounded"></img>
                    <p class="mt-2 text-center text-black font-semibold">Project Five</p>
                </div>
                <!-- Duplicated items for seamless loop -->
                <div class="flex-shrink-0">
                    <img src="https://images.unsplash.com/photo-1767449985562-013c41bd7fda?q=80&w=1035&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" class="w-80 h-100 bg-gray-300 rounded"></img>
                    <p class="mt-2 text-center text-black font-semibold">Project One</p>
                </div>
                <div class="flex-shrink-0">
                    <img src="https://images.unsplash.com/photo-1764649841485-82d7bd92760a?q=80&w=987&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" class="w-80 h-100 bg-gray-300 rounded"></img>
                    <p class="mt-2 text-center text-black font-semibold">Project Two</p>
                </div>
                <div class="flex-shrink-0">
                    <img src="https://images.unsplash.com/photo-1765004775664-24306ca36b8f?w=900&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxmZWF0dXJlZC1waG90b3MtZmVlZHwxNHx8fGVufDB8fHx8fA%3D%3D" class="w-80 h-100 bg-gray-300 rounded"></img>
                    <p class="mt-2 text-center text-black font-semibold">Project Three</p>
                </div>
                <div class="flex-shrink-0">
                    <img src="https://images.unsplash.com/photo-1764966894769-4b2944571d12?q=80&w=1065&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" class="w-80 h-100 bg-gray-300 rounded"></img>
                    <p class="mt-2 text-center text-black font-semibold">Project Four</p>
                </div>
                <div class="flex-shrink-0">
                    <img src="https://images.unsplash.com/photo-1765834082477-5f9c1466a7c4?w=900&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxmZWF0dXJlZC1waG90b3MtZmVlZHwyMXx8fGVufDB8fHx8fA%3D%3D" class="w-80 h-100 bg-gray-300 rounded"></img>
                    <p class="mt-2 text-center text-black font-semibold">Project Five</p>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
@keyframes scroll {
  0% {
    transform: translateX(0);
  }
  100% {
    transform: translateX(calc(-320px * 5 - 16px * 5));
  }
}

.auto-scroll {
  animation: scroll 30s linear infinite;
}
</style>