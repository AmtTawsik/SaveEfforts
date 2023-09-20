<template>
    <div>
        <footer>
            <div
                class="flex flex-col items-center grid-cols-2 gap-10 px-4 py-10 mx-auto sm:justify-around sm:flex-row max-w-screen-2xl sm:px-8">
                <div class="">
                    <div class="flex items-center justify-center gap-2 lg:justify-start"><img :src="logo"
                            alt="logo" class="w-12">
                        <h4 class="text-xl font-bold">SaveEfforts.com</h4>
                    </div>
                    <p class="mt-3 text-gray-700">Save Efforts & time with automations</p>
                </div>
                <div class="flex flex-col items-center gap-5 sm:items-start">
                    <h5 class="text-lg font-semibold">Get in Touch</h5>
                    <ul class="flex flex-col items-center gap-5 font-medium text-gray-800 sm:items-start">
                        <li class="flex items-center gap-2"><svg xmlns="http://www.w3.org/2000/svg" fill="none"
                                viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true"
                                class="w-6 h-6">
                                <path stroke-linecap="round" stroke-linejoin="round"
                                    d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 002.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 01-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 00-1.091-.852H4.5A2.25 2.25 0 002.25 4.5v2.25z">
                                </path>
                            </svg> +441908103333</li>
                        <li class="flex items-center gap-2"><svg xmlns="http://www.w3.org/2000/svg" fill="none"
                                viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true"
                                class="w-6 h-6">
                                <path stroke-linecap="round" stroke-linejoin="round"
                                    d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25h-15a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5h-15a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75">
                                </path>
                            </svg> aiautomation@saveefforts.com</li>
                        <li class="flex items-center gap-2"><svg xmlns="http://www.w3.org/2000/svg" fill="none"
                                viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true"
                                class="w-6 h-6">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M15 10.5a3 3 0 11-6 0 3 3 0 016 0z">
                                </path>
                                <path stroke-linecap="round" stroke-linejoin="round"
                                    d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1115 0z"></path>
                            </svg> Milton Keyens, United Kingdom</li>
                    </ul>
                </div>
            </div>
            <div
                class="flex flex-col flex-wrap justify-between w-full gap-5 px-1 py-5 border-t sm:items-center sm:flex-row sm:px-16 border-t-gray-200">
                <div class="text-sm font-medium text-gray-500"> SaveEfforts.com © 2023 All rights reserved </div>
                <div class="text-sm font-medium text-gray-500"> SaveEfforts is brand name of Qualyval Ltd is a company registered in England & Wales.</div><NuxtLink href="/privacy-policy"
                    class="text-sm font-medium text-gray-500"> PRIVACY POLICY </NuxtLink>
            </div>
        </footer>
    </div>
</template>

<script setup>
import logo from 'assets/images/logo.svg'
</script>