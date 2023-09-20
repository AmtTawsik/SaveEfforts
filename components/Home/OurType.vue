<template>
    <div class="bg-[#000837] py-10">
        <h2 class="text-center text-white text-3xl md:text-5xl font-bold">Our typical engagement process</h2>
        <div class="w-11/12 mx-auto flex md:flex-row flex-col items-center">
            <img class="w-56 md:hidden" :src="p1" alt="">
            <img class="hidden md:block" :src="p1" alt="">
            <div class="flex md:flex-row flex-col items-center gap-5">
                <div>
                    <img :src="p2" alt="">
                    <h4 class="text-2xl md:text-4xl font-semibold mt-2 text-white text-center">Analysis</h4>
                </div>
                <img class="w-16 md:mx-5 transform rotate-90 md:rotate-0" :src="arrow" alt="">
                <div>
                    <img :src="p3" alt="">
                    <h4 class="text-2xl md:text-4xl font-semibold mt-2 text-white">Suggestions & Proposal</h4>
                </div>
                <img class="w-16 md:mx-5 transform rotate-90 md:rotate-0" :src="arrow" alt="">
                <div>
                    <img :src="p4" alt="">
                    <h4 class="text-2xl md:text-4xl font-semibold mt-2 text-white text-center">Automation</h4>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
import p1 from 'assets/images/leady.webp'
import p2 from 'assets/images/pc.webp'
import arrow from 'assets/images/arrow2.webp'
import p3 from 'assets/images/board.webp'
import p4 from 'assets/images/right.svg'
</script>