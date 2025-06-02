<template>

  <header class="w-full h-[80px]  bg-white ">

    <div
      class="flex flex-row gap-10 h-full max-w-[1440px] mx-auto py-4 px-2 transition items-center justify-between relative group overflow-hidden">

      <div class="sticky flex">
        <img src="public/images/Image 203.png" alt="">
        <h1 class=" mt-4 text-sm font-bold">POKE NOW.</h1>
      </div>

      <div class="lg:hidden relative">
        <button @click="isDropdownOpen = !isDropdownOpen" class="bg-orange-600 text-white px-4 py-2 rounded">
          Menu
        </button>

        <div v-if="isDropdownOpen"
          class="fixed top-0 z-50 left-0 mt-2 w-[90vw] max-w-xs bg-white shadow-lg rounded border border-gray-200 transition-all">
          <ul class="flex flex-col divide-y divide-gray-100 p-2">
            <li v-for="item in menuItems" :key="item.path">
              <NuxtLink :to="item.path"
                class="block py-3 px-4 text-sm text-black hover:bg-orange-100 hover:text-orange-600"
                @click="isDropdownOpen = false">
                {{ item.name }}
              </NuxtLink>
            </li>
            <li class="px-4 pt-4">
              <NuxtLink>
                <button class="w-full border border-black py-2 rounded hover:bg-black hover:text-white transition">
                  Order Online
                </button>
              </NuxtLink>
            </li>
            <li class="px-4 py-4">
              <NuxtLink>
                <button class="w-full bg-black text-white py-2 rounded-full hover:bg-gray-800 transition">
                  Book a Table
                </button>
              </NuxtLink>
            </li>
          </ul>
        </div>
      </div>



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
import { ref } from 'vue'
const isDropdownOpen = ref(false)
const menuItems = [
  { name: 'Home', path: '/home' },
  { name: 'Menu', path: '/menu' },
  { name: 'Our story', path: '/our-story' },
  { name: 'Location', path: '/location' },
  { name: 'Gift card', path: '/gift-card' }
]
</script>