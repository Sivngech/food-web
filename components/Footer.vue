<template>
    <footer class="w-full " style="background-color:#171A1F ;">
        <div class="max-w-[1440px] mx-auto flex  flex-col md:flex-row gap-10 md:gap-20 py-10 px-10">

            <div class="justify-between">
                <div class="sticky flex  w-[263px] h-[75px] text-white">
                    <img src="public/images/Company Logo.png" alt="">
                    <h1 class="mt-5 font-bold text-lg">POKE NOW.</h1>
                </div>
                <nav class="flex gap-20 items-center mt-5">
                    <ul class="flex flex-col sm:flex-row gap-3 sm:gap-6 ">
                        <li v-for="item in menuItems" :key="item.path">
                            <NuxtLink :to="item.path" class="hover:underline text-white">
                                {{ item.name }}
                            </NuxtLink>
                        </li>

                    </ul>
                </nav>
                <p class="text-white mt-10">© 2022 Brand, Inc. • Privacy • Terms • Sitemap</p>
            </div>

            <div>

                <div>
                    <div class="flex gap-5">
                        <div>
                            <NuxtLink><button class="py-2 px-2 rounded-full hover:bg-white hover:text-red-300"
                                    style="color: #F96540;border:solid #F96540">Order Online</button></NuxtLink>
                        </div>
                        <div>
                            <NuxtLink><button class=" text-white rounded-full py-2 px-2 hover:bg-black hover:text-red-300 sm:w-auto"
                                    style="background:#F96540;">Book a
                                    Table</button></NuxtLink>
                        </div>
                    </div>
                    <p class="text-white mt-5">848 King Street, Mesa, AZ 85201, Boston, USA</p>
                    <p class="text-white mt-5">info@pokebar.com</p>

                    <div class="flex flex-row mt-5 gap-5">
                        <img src="public/images/twitter.png" alt="">
                        <img src="public/images/facebook.png" alt="">
                        <img src="public/images/linkedin.png" alt="">
                        <img src="public/images/youtube.png" alt="">
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>
<script setup>
const menuItems = [
    { name: 'Home', path: '/home' },
    { name: 'Menu', path: '/menu' },
    { name: 'Our story', path: '/our-story' },
    { name: 'Location', path: '/location' },
    { name: 'Gift card', path: '/gift-card' }
]
</script>