<template>
    <div class="bg-[#000837] py-10">
        <h2 class="text-center text-3xl md:text-6xl font-bold text-[#FAC300] my-8 md:my-16 pt-10">Our Experience</h2>
        <div class="grid grid-cols-12 w-11/12 md:w-10/12 mx-auto text-white text-xl md:text-3xl md:gap-x-16 gap-y-10 mb-20 md:mb-52">
            <div class="col-span-12 md:col-span-6 flex items-center">
                <img :src="p1" alt="">
                <p class="ml-2">200+ Processes automated</p>
            </div>
            <div class="col-span-12 md:col-span-6 flex items-center md:ml-16">
                <img :src="p2" alt="">
                <p class="ml-2">10+ Digital platform delivered</p>
            </div>
            <div class="col-span-12 md:col-span-6 flex items-center">
                <img :src="p3" alt="">
                <p class="ml-2">100+ platforms integrated</p>
            </div>
            <div class="col-span-12 md:col-span-6 flex items-center md:ml-16">
                <img :src="p4" alt="">
                <p class="ml-2">50+ Clients</p>
            </div>
        </div>
    </div>
</template>

<script setup>
import p1 from 'assets/images/logos/p1.webp'
import p2 from 'assets/images/logos/p2.webp'
import p3 from 'assets/images/logos/p3.webp'
import p4 from 'assets/images/logos/p4.webp'
</script>