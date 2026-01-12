<script setup>
import BlueTextBody from './BlueTextBody.vue';


</script>

<template>
    <section class="px-8">
        <div class="flex flex-col items-center">
            <BlueTextBody>
                <h1 class="text-4xl font-extrabold">PRICING_</h1>
            </BlueTextBody>
            <h1 class="text-5xl font-extrabold pt-8">Flexible plans<br> for every step</h1>
            <div class="py-8">
                <button class="bg-black text-white text-2xl px-3 py-2 rounded-4xl">See All Pricing</button>
            </div>
            <div class="px-4 py-4 bg-gray-100 max-w-xl">
                <div class="flex flex-col gap-4 py-8 px-4 bg-white shadow-lg rounded-lg">
                    <h2 class="font-extrabold text-3xl">Weekly Retainer</h2>
                    <p class="font-extrabold text-xl">Perfect for fast-moving founders who need hands-on design support,
                        week by week.</p>
                    <span class="text-4xl font-extrabold pt-4 pb-2">$2590
                        /month</span>
                </div>
                <div class="flex gap-2 py-4">
                    <button
                        class="flex-1 flex items-center justify-center gap-2 bg-orange-600 hover:bg-blue-500 text-white text-xl px-3 py-2 rounded-4xl shadow-lg shadow-full">
                        <i class="pi pi-calendar"></i>
                        Start today
                    </button>

                    <button
                        class="flex-1 flex items-center justify-center gap-2 bg-white hover:bg-orange-600 hover:text-white text-black text-xl px-3 py-2 rounded-4xl shadow-lg shadow-full">
                        <i class="pi pi-calendar"></i>
                        Book a call
                    </button>
                </div>
                <div class="flex flex-col gap-4 py-8 px-4 bg-white shadow-lg rounded-lg">
                    <div class="flex items-center gap-2">
                        <i class="pi pi-check"></i>
                        <h3>Rapid UX Audit & Journey Mapping</h3>
                    </div>
                    <div class="flex items-center gap-2">
                        <i class="pi pi-check"></i>
                        <h3>Rapid UX Audit & Journey Mapping</h3>
                    </div>
                    <div class="flex items-center gap-2">
                        <i class="pi pi-check"></i>
                        <h3>Rapid UX Audit & Journey Mapping</h3>
                    </div>
                    <div class="flex items-center gap-2">
                        <i class="pi pi-check"></i>
                        <h3>Rapid UX Audit & Journey Mapping</h3>
                    </div>
                    <div class="flex items-center gap-2">
                        <i class="pi pi-check"></i>
                        <h3>Rapid UX Audit & Journey Mapping</h3>
                    </div>
                </div>

            </div>
            <div class="pt-4">
                <div class="px-4 py-4 bg-gray-100">
                    <div class="max-w-xl flex flex-col gap-4 py-8 px-4 bg-white shadow-lg rounded-lg">
                        <h2 class="font-extrabold text-3xl">Custom Project</h2>
                        <p class="font-extrabold text-xl">
                            Don’t need the full package? We also handle one-off projects for bigger or smaller scopes
                        </p>
                    </div>
                    <div class="flex gap-2 py-4">
                        <button
                            class="flex-1 flex items-center justify-center gap-2 bg-white hover:bg-orange-600 text-black text-xl px-3 py-2 rounded-4xl shadow-lg shadow-full">
                            <i class="pi pi-chat"></i>
                            Get a quote
                        </button>

                        <button
                            class="flex-1 flex items-center justify-center gap-2 bg-white hover:bg-orange-600 hover:text-white text-black text-xl px-3 py-2 rounded-4xl shadow-lg shadow-full">
                            <i class="pi pi-mail"></i>
                            Email us
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>