<template>
    <div class="bg-[#000837] max-w-screen py-5">
        <div class="flex items-center justify-center mb-5 md:mb-0">
            <img class="md:w-32 w-16" :src="logo" alt="">
            <h2 class="text-center text-2xl md:text-7xl font-bold text-white">Save<span
                    class="text-[#FFC03D]">Efforts</span>.com</h2>
        </div>
        <div class="grid grid-cols-12 items-center w-11/12 mx-auto">
            <section class="col-span-4">
                <img class="w-full" :src="p1" alt="">
            </section>
            <section class="col-span-4">
                <div class="flex justify-center">
                    <img class="w-full md:-mt-5" :src="arrow" alt="">
                </div>
                <h4 class="text-xl font-bold md:text-5xl text-center text-white">Al & Automation</h4>
            </section>
            <section class="col-span-4">
                <img class="w-full" :src="p2" alt="">
            </section>
        </div>
        <div class="mt-5 md:mt-0">
            <h3 class="text-center text-white text-2xl md:text-4xl font-bold">Operate Business like Uber i.e. Automated &
                Scalable</h3>
        </div>
        <div class="flex md:flex-row flex-col w-11/12 mx-auto items-center mt-5 py-5 gap-5">
            <img class="w-72" :src="reviewer" alt="">
            <div>
                <img class="md:w-96 w-48 mb-1" :src="star" alt="">
                <p class="text-lg md:text-2xl text-white">Earlier this month my team implemented their first automation. Concept to implementation was less than 60 days and ROI will exceed 600%! Most importantly, it eliminates repetitive daily tasks to drive better customer and employee experience.</p>
            </div>
        </div>
    </div>
</template>

<script setup>
import p1 from 'assets/images/left.svg'
import p2 from 'assets/images/right.svg'
import logo from 'assets/images/logo.svg'
import arrow from 'assets/images/arrow.webp'
import reviewer from 'assets/images/reviewer.svg'
import star from 'assets/images/star.webp'
</script>