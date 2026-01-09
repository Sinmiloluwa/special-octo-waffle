<script setup>
import BlueTextBody from './BlueTextBody.vue';
</script>

<template>
    <section class="py-16">
        <BlueTextBody>
            <span class="text-xl uppercase py-4">Projects_</span>
        </BlueTextBody>
        <div class="flex justify-between py-8">
            <h1 class="text-7xl text-black font-black mb-4">Work that clearly<br> drives impact</h1>
            <div class="flex flex-col gap-8">
                <h3 class="text-2xl text-gray-400 text-start">With over a decade of global experience, <br> we deliver a
                    wide range of creative<br> and strategic solutions.</h3>
                <button class="mt-4 bg-orange-500 text-white px-4 py-2  rounded-4xl hover:bg-orange-600 w-40">View All
                    work</button>
            </div>
        </div>

        <div class="mx-auto">
            <div class="columns-1 sm:columns-2 lg:columns-3 xl:columns-4 gap-5 lg:gap-8">

                <div class="space-y-32">
                    <div>
                        <h3 class="font-bold">Brandlift. <span class="text-gray-400 font-normal ml-2">Strategy, Web
                                Design</span></h3>
                        <img src="https://images.unsplash.com/photo-1534447677768-be436bb09401?q=80&w=600"
                            class="mt-4 w-full object-cover aspect-[4/5]" alt="Eagle">
                    </div>
                    <div>
                        <h3 class="font-bold">Creatix. <span class="text-gray-400 font-normal ml-2">Strategy, Web
                                Design</span></h3>
                        <img src="https://images.unsplash.com/photo-1464822759023-fed622ff2c3b?q=80&w=600"
                            class="mt-4 w-full object-cover aspect-[4/5]" alt="Flowers">
                    </div>
                </div>

                <div class="space-y-32 lg:mt-12 ">
                    <div>
                        <h3 class="font-bold">Webspire. <span class="text-gray-400 font-normal ml-2">Strategy, Web
                                Design</span></h3>
                        <img src="https://images.unsplash.com/photo-1541701494587-cb58502866ab?q=80&w=600"
                            class="mt-4 w-full h-48 object-cover aspect-[3/4]" alt="Sculpture">
                    </div>
                    <div>
                        <h3 class="font-bold">Designo. <span class="text-gray-400 font-normal ml-2">Strategy, Web
                                Design</span></h3>
                        <img src="https://images.unsplash.com/photo-1550745165-9bc0b252726f?q=80&w=600"
                            class="mt-4 w-full object-cover aspect-square" alt="Hardware">
                    </div>
                </div>

                <div class="lg:mt-64">
                    <div>
                        <h3 class="font-bold">Campayn. <span class="text-gray-400 font-normal ml-2">Strategy, Web
                                Design</span></h3>
                        <img src="https://images.unsplash.com/photo-1527443224154-c4a3942d3acf?q=80&w=600"
                            class="mt-4 w-full object-cover aspect-square" alt="Keyboard">
                    </div>
                </div>

                <div class="space-y-12 lg:mt-32">
                    <div>
                        <h3 class="font-bold">UXora. <span class="text-gray-400 font-normal ml-2">Strategy, Web
                                Design</span></h3>
                        <img src="https://images.unsplash.com/photo-1515886657613-9f3515b0c78f?q=80&w=600"
                            class="mt-4 w-full object-cover aspect-[4/5]" alt="Abstract Art">
                    </div>
                    <div>
                        <h3 class="font-bold">Pixelwave. <span class="text-gray-400 font-normal ml-2">Strategy, Web
                                Design</span></h3>
                        <img src="https://images.unsplash.com/photo-1579783902614-a3fb3927b6a5?q=80&w=600"
                            class="mt-4 w-full object-cover aspect-square" alt="Concrete sculpture">
                    </div>
                </div>

            </div>
        </div>
    </section>
</template>