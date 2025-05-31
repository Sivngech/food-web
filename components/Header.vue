<template>

    <header class="w-full h-[80px]  bg-white ">

        <div
            class="flex flex-row gap-10 h-full max-w-[1440px] mx-auto py-4 px-2 transition items-center justify-between relative group ">

            <div class="sticky flex">
                <img src="public/images/Image 203.png" alt="">
                <h1 class=" mt-4 text-sm font-bold">POKE NOW.</h1>
            </div>

            <button type="button" class="block lg:hidden bg-orange-600 text-white px-4 py-2 rounded">
                Menu
            </button>

            <nav class="hidden lg:flex gap-20 items-center">
                <ul class="flex gap-20" role="none">
                    <li v-for="item in menuItems" :key="item.path">
                        <NuxtLink :to="item.path" class="text-black" exact-active-class="nav-active">
                            {{ item.name }}
                        </NuxtLink>
                    </li>

                </ul>
            </nav>


            <div class="hidden lg:flex gap-5">
                <div>
                    <NuxtLink><button class="py-2 px-2 w-[125px] h-[44px]">Order Online</button></NuxtLink>
                </div>
                <div>
                    <NuxtLink><button class="bg-black text-white rounded-full py-2 px-2 h-[44px] w-[126px]">Book a
                            Table</button></NuxtLink>
                </div>
            </div>


        </div>
    </header>

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