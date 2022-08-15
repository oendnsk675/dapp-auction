<template>
  <div class="bg-gradient-to-br from-secondary to-primary font-sans">
    <nav class="w-full px-10 py-4 flex items-center justify-between border-b pb-4 border-opacity-20 border-white">
        <!-- logo -->
        <div class="flex gap-3 items-center">
            <img src="~/assets/logo.png" alt="">
            <h2 class="text-2xl font-bold text-white">CosLab</h2>
        </div>
        <!-- logo -->

        <div class="flex gap-6">
            <a href="" class="text-gray-300 font-semibold text-lg">
                Home
            </a>

            <a href="" class="text-gray-300 font-semibold text-lg">
                Discover
            </a>

            <a href="" class="text-gray-300 font-semibold text-lg">
                About
            </a>
        </div>

        <div class="flex gap-8 items-center">
            <a href="" class="text-gray-300 font-semibold text-lg">
                Login
            </a>

            <a href="" class="text-gray-50 px-4 py-2 bg-opacity-60 bg-secondary2 rounded-lg font-semibold hover:bg-opacity-100 transition-all duration-300 ease-out">
                Get Started
            </a>
        </div>
    </nav>

    <section class="flex mb-32 gap-10 p-24 justify-around pt-32">
        <div class="w-2/5">
            <h1 class="text-6xl font-bold text-gray-300 font-sans">
                Lets Find Some Awsome Product
            </h1>

            <div class="mt-20">
                <button class="px-6 py-3 text-xl rounded-xl font-semibold text-gray-50 transition-all duration-300 ease-out bg-secondary2 hover:bg-opacity-100 bg-opacity-50">Get Started</button>
            </div>
        </div>

        <div class="w-1/3 relative">
            <!-- card -->
            <div class="bg-indigo-400 bg-opacity-80 absolute left-5 w-full -top-10 z-20 rounded-lg h-96 p-6">
                <div class="bg-indigo-100 rounded-md h-full w-full flex justify-center items-center relative">
                    <div class="w-44">
                        <img src="~/assets/boba.png" alt="" class="w-full">
                    </div>

                    <div class="w-full bg-indigo-400 bg-opacity-50 gap-7 flex py-1 px-4 absolute bottom-0 left-0">
                        <!-- current bid -->
                        <div>
                            <div>
                                <span class="block text-lg font-semibold">Rp100.000</span>
                                <span class="block text-sm">Current Bid</span>
                            </div>
                        </div>
                        <!-- current bid -->
                        
                        <!-- bid count -->
                        <div>
                            <div>
                                <span class="block text-lg font-semibold">100</span>
                                <span class="block text-sm">Bid Count</span>
                            </div>
                        </div>
                        <!-- bid count -->
                    </div>
                </div>
            </div>
            <!-- card -->

            <!-- card-shadow -->
            <div class="bg-indigo-400 bg-opacity-30 absolute left-0 w-full -top-5 z-10 rounded-lg h-96"></div>
            <!-- card-shadow -->
        </div>

        <div class="absolute right-10 top-28">
            <img src="~/assets/astr.png" alt="" class="w-full">
        </div>
    </section>

    <section class="mb-20 w-full">
        <h1 class="text-4xl text-gray-50 text-center">Top Deals Over Last 7 Days</h1>

        <div class="w-full mt-12 flex justify-center gap-10">
            <div class="w-1/4">
                <div class="flex gap-6 items-center mb-6">
                    <h2 class="text-xl font-bold text-white">1</h2>
                    <div class="flex gap-6">
                        <div class="w-14 h-14 overflow-hidden bg-indigo-400 bg-opacity-70 rounded-md">
    
                        </div>
                        <div class="text-gray-50">
                            <span class="font-semibold">Sollet</span>
                            <span class="text-sm block font-semibold">Rp1000.000</span>
                        </div>
                    </div>
                </div>
                <div class="flex gap-6 items-center mb-6">
                    <h2 class="text-xl font-bold text-white">2</h2>
                    <div class="flex gap-6">
                        <div class="w-14 h-14 overflow-hidden bg-indigo-400 bg-opacity-70 rounded-md">
    
                        </div>
                        <div class="text-gray-50">
                            <span class="font-semibold">Sollet</span>
                            <span class="text-sm block font-semibold">Rp1000.000</span>
                        </div>
                    </div>
                </div>
                <div class="flex gap-6 items-center mb-6">
                    <h2 class="text-xl font-bold text-white">3</h2>
                    <div class="flex gap-6">
                        <div class="w-14 h-14 overflow-hidden bg-indigo-400 bg-opacity-70 rounded-md">
    
                        </div>
                        <div class="text-gray-50">
                            <span class="font-semibold">Sollet</span>
                            <span class="text-sm block font-semibold">Rp1000.000</span>
                        </div>
                    </div>
                </div>
            </div>

            <div class="w-1/4">
                <div class="flex gap-6 items-center mb-6">
                    <h2 class="text-xl font-bold text-white">4</h2>
                    <div class="flex gap-6">
                        <div class="w-14 h-14 overflow-hidden bg-indigo-400 bg-opacity-70 rounded-md">
    
                        </div>
                        <div class="text-gray-50">
                            <span class="font-semibold">Sollet</span>
                            <span class="text-sm block font-semibold">Rp1000.000</span>
                        </div>
                    </div>
                </div>
                <div class="flex gap-6 items-center mb-6">
                    <h2 class="text-xl font-bold text-white">5</h2>
                    <div class="flex gap-6">
                        <div class="w-14 h-14 overflow-hidden bg-indigo-400 bg-opacity-70 rounded-md">
    
                        </div>
                        <div class="text-gray-50">
                            <span class="font-semibold">Sollet</span>
                            <span class="text-sm block font-semibold">Rp1000.000</span>
                        </div>
                    </div>
                </div>
                <div class="flex gap-6 items-center mb-6">
                    <h2 class="text-xl font-bold text-white">6</h2>
                    <div class="flex gap-6">
                        <div class="w-14 h-14 overflow-hidden bg-indigo-400 bg-opacity-70 rounded-md">
    
                        </div>
                        <div class="text-gray-50">
                            <span class="font-semibold">Sollet</span>
                            <span class="text-sm block font-semibold">Rp1000.000</span>
                        </div>
                    </div>
                </div>
            </div>

            <div class="w-1/4">
                <div class="flex gap-6 items-center mb-6">
                    <h2 class="text-xl font-bold text-white">7</h2>
                    <div class="flex gap-6">
                        <div class="w-14 h-14 overflow-hidden bg-indigo-400 bg-opacity-70 rounded-md">
    
                        </div>
                        <div class="text-gray-50">
                            <span class="font-semibold">Sollet</span>
                            <span class="text-sm block font-semibold">Rp1000.000</span>
                        </div>
                    </div>
                </div>
                <div class="flex gap-6 items-center mb-6">
                    <h2 class="text-xl font-bold text-white">8</h2>
                    <div class="flex gap-6">
                        <div class="w-14 h-14 overflow-hidden bg-indigo-400 bg-opacity-70 rounded-md">
    
                        </div>
                        <div class="text-gray-50">
                            <span class="font-semibold">Sollet</span>
                            <span class="text-sm block font-semibold">Rp1000.000</span>
                        </div>
                    </div>
                </div>
                <div class="flex gap-6 items-center mb-6">
                    <h2 class="text-xl font-bold text-white">9</h2>
                    <div class="flex gap-6">
                        <div class="w-14 h-14 overflow-hidden bg-indigo-400 bg-opacity-70 rounded-md">
    
                        </div>
                        <div class="text-gray-50">
                            <span class="font-semibold">Sollet</span>
                            <span class="text-sm block font-semibold">Rp1000.000</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <img src="~/assets/wave.svg" alt="">
    <footer class="relative bg-footer pb-5">
        <div class="flex justify-between px-16">
            <div class="w-1/3">
                <h1 class="text-5xl text-gray-50 font-bold font-sans">
                    Reliable and Safe, that's us
                </h1>
            </div>

            <div class="flex text-white font-sans mb-14 flex-col justify-end">
                <div class="flex gap-10 mb-10 ">
                    <a href="" class="hover:opacity-70 transition-all duration-300">PRIVACY PLOICY</a>
                    <a href="" class="hover:opacity-70 transition-all duration-300">TERMS & CONDITIONS</a>
                    <a href="" class="hover:opacity-70 transition-all duration-300">ABOUT US</a>
                    <a href="" class="hover:opacity-70 transition-all duration-300">FAQ</a>
                </div>

                <div class="flex gap-6 justify-end">
                    <a href="" class="w-13 h-13 hover:bg-opacity-80 transition-all duration-300 p-2.5 rounded bg-indigo-700 bg-opacity-50">
                        <div class="w-full h-full rounded">
                            <img src="~/assets/fb.svg" alt="" class="w-full h-full">
                        </div>
                    </a>
                    <a href="" class="w-13 h-13 hover:bg-opacity-80 transition-all duration-300 p-2.5 rounded bg-indigo-700 bg-opacity-50">
                        <div class="w-full h-full rounded">
                            <img src="~/assets/ig.svg" alt="" class="w-full h-full">
                        </div>
                    </a>
                    <a href="" class="w-13 h-13 hover:bg-opacity-80 transition-all duration-300 p-2.5 rounded bg-indigo-700 bg-opacity-50">
                        <div class="w-full h-full rounded">
                            <img src="~/assets/mail.svg" alt="" class="w-full h-full">
                        </div>
                    </a>
                </div>
            </div>
        </div>

        <hr class="opacity-30 my-6">

        <div class="w-full font-sans font-semibold text-white flex justify-center">
            Created with <span class="text-red-400"> ❤ </span> By Sayidina Ahmadal Qososyi
        </div>
    </footer>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>