<script setup>

</script>

<template>
    <nav>
        <div class="flex justify-between items-center bg-transparent text-black py-4">
            <div class="flex items-center gap-2">
                <i class="pi pi-spin pi-cog" style="font-size: 2rem"></i>
                <h1>Boldark</h1>
            
            </div>
            <ul class="flex gap-4">
                <li><a href="#" class="hover:text-gray-400 border-b border-orange-600 rounded-4xl px-4 py-2">Home</a></li>
                <li><a href="#" class="hover:text-gray-400 ">About</a></li>
                <li><a href="#" class="hover:text-gray-400 ">Projects</a></li>
                <li><a href="#" class="hover:text-gray-400 ">Pricing</a></li>
                <li><a href="#" class="hover:text-gray-400 ">Pages</a><i class="pi pi-angle-down"></i></li>
            </ul>
            <div class="flex items-center gap-8">
                <a href="#" class="hover:text-gray-400 text-2xl"><i class="pi pi-shopping-cart"></i></a>
                <button class="bg-orange-500 text-white px-4 py-2  rounded-4xl hover:bg-orange-600">Contact Us</button>
            </div>
        </div>
    </nav>
</template>