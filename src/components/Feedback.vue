<script setup>
import BlueTextBody from './BlueTextBody.vue';


</script>

<template>
    <section class="py-16 px-8">
        <BlueTextBody>
            <h1 class="font-extrabold text-2xl">CLIENT FEEDBACK_</h1>
        </BlueTextBody>
        <div class="flex justify-between pb-16">
            <h1 class="font-extrabold text-4xl">Hear from our valued partners</h1>
            <h3 class="text-3xl font-extrabold max-w-2xl">The succcess of our clients is our greatest accomplishment.
                Here is what they have to say</h3>
        </div>
        <div class="relative overflow-hidden">
            <div class="flex gap-6 overflow-x-auto scroll-smooth snap-x snap-mandatory no-scrollbar">
                <div class="min-w-[70%] snap-start border border-gray-200 bg-gray-300 py-4 px-4 max-w-5xl mt-10">
                    <div class="flex justify-between py-4">
                        <div class="flex justify-evenly gap-4">
                            <h2 class="font-extrabold">Brightwave</h2>
                            <p>.Branding</p>
                            <p>.Product Design</p>
                            <p class="font-extrabold">.Web Design</p>
                        </div>
                        <div class="">
                            <h2>2024</h2>
                        </div>
                    </div>
                    <div class="border border-gray-100 bg-white py-8">
                        <h2 class="text-4xl font-extrabold text-center p-16">"Working with this studio was a
                            game-changer. Their creativity, strategic approach, and attention to detail transformed our
                            brand and boosted our online presence. They truly understand how to bring ideas to life and
                            deliver exceed expectations."</h2>
                        <div class="flex justify-between">
                            <div class="flex items-center gap-2 px-6">
                                <img class="w-16 h-16 rounded-full object-cover"
                                    src="https://images.unsplash.com/photo-1605369572399-05d8d64a0f6e?w=900&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTJ8fGhlYWQlMjBzaG90fGVufDB8fDB8fHww">
                                <div class="flex flex-col justify-end">
                                    <h3 class="text-2xl">James Carter</h3>
                                    <p>Product Manager, NovaTech Solutions</p>
                                </div>

                            </div>
                            <div class="px-4">
                                <h3 class="text-3xl">Logopisium</h3>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="min-w-[70%] snap-start border border-gray-200 bg-gray-300 py-4 px-4 max-w-5xl mt-10">
                    <div class="flex justify-between py-4">
                        <div class="flex justify-evenly gap-4">
                            <h2 class="font-extrabold">Brightwave</h2>
                            <p>.Branding</p>
                            <p>.Product Design</p>
                            <p class="font-extrabold">.Web Design</p>
                        </div>
                        <div class="">
                            <h2>2024</h2>
                        </div>
                    </div>
                    <div class="border border-gray-100 bg-white py-8">
                        <h2 class="text-4xl font-extrabold text-center p-16">"Working with this studio was a
                            game-changer. Their creativity, strategic approach, and attention to detail transformed our
                            brand and boosted our online presence. They truly understand how to bring ideas to life and
                            deliver exceed expectations."</h2>
                            <div class="flex justify-between">
                            <div class="flex items-center gap-2 px-6">
                                <img class="w-16 h-16 rounded-full object-cover"
                                    src="https://images.unsplash.com/photo-1605369572399-05d8d64a0f6e?w=900&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTJ8fGhlYWQlMjBzaG90fGVufDB8fDB8fHww">
                                <div class="flex flex-col justify-end">
                                    <h3 class="text-2xl">James Carter</h3>
                                    <p>Product Manager, NovaTech Solutions</p>
                                </div>

                            </div>
                            <div class="px-4">
                                <h3 class="text-3xl">Logopisium</h3>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="pointer-events-none absolute top-0 right-0 h-full w-40 
              bg-gradient-to-l from-white via-white/80 to-transparent">
            </div>
        </div>

    </section>
</template>

<style scoped>
.no-scrollbar {
    -ms-overflow-style: none;
    /* IE & Edge */
    scrollbar-width: none;
    /* Firefox */
}

.no-scrollbar::-webkit-scrollbar {
    display: none;
    /* Chrome, Safari */
}
</style>