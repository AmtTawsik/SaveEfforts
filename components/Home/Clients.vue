<template>
    <div class="w-11/12 mx-auto my-10 md:my-20">
        <h2 class="text-center text-3xl md:text-5xl font-bold md:w-8/12 mx-auto">Trusted by fast-moving companies and teams around the world</h2>
        <div class="flex flex-wrap items-center justify-around w-full gap-5 font-semibold my-5">
            <img class="w-32 duration-200 lg:hover:scale-110" :src="p1" alt="fendi">
            <img class="w-36 duration-200 lg:hover:scale-110" :src="p2" alt="pernod_richerd">
            <img class="w-48 duration-200 lg:hover:scale-110" :src="p3" alt="world_duyy_free">
            <img class="w-32 duration-80 lg:hover:scale-110" :src="p4" alt="SLEEK">
            <img class="w-32 duration-200 lg:hover:scale-110" :src="p5" alt="viadex">
        </div>
    </div>
</template>

<script setup>
import p1 from 'assets/images/clients/fendi.webp'
import p2 from 'assets/images/clients/pernod_richerd.webp'
import p3 from 'assets/images/clients/world_duyy_free.webp'
import p4 from 'assets/images/clients/SLEEK.webp'
import p5 from 'assets/images/clients/viadex.webp'
</script>
