<template>
    <div class="container mx-auto px-4 py-8">
    <section>
        <div class="flex flex-col-reverse lg:flex-row gap-10">
            <div class="w-full lg:w-1/2">
                <h1 class="text-3xl md:text-4xl font-bold mb-2 overflow-hidden">Give the Perfect Gift</h1>
                <p class="text-base md:text-lg">Get a voucher for yourself or gift one to a friend</p>
                <p class="text-xl mt-5 font-semibold">What kind of gift is it?</p>
                <div class="mt-4 flex flex-col gap-5">
                    <div class="flex items-center gap-4 p-4 border rounded max-w-full"
                        style="border-color: #F96540;color:#171A1F;">
                        <img src="public/images/Gift-Icon.png" alt="" class="w-9">
                        <div class="flex flex-col  ">
                            <h1 class="text-lg font-semibold">For one individual</h1>
                            <p class="text-sm">Send a gift card to one recipient</p>
                        </div>
                    </div>
                    <div class="flex items-center gap-4 p-4 border rounded max-w-full"
                        style="border-color: #BCC1CA;color:#171A1F;">
                        <img src="public/images/Diversity-Icon.png" alt="" class="w-9">
                        <div class="flex flex-col">
                            <h1 class="text-lg font-semibold">Group gift card</h1>
                            <p class="text-sm">Pool money from multiple contributors for one recipient</p>
                        </div>
                    </div>
                </div>

                <h1 class="text-xl mt-6 font-semibold">eGift card amount</h1>
                <div class="border rounded flex  flex-nowrap gap-2  p-1 max-w-[396px] mx-auto" style="border-color: #FCDD80;">
                    <div class="border-r px-2 py-1 sm:text-xl" style="border-color: #FCDD80;"><button class="mt-1 sm:text-center sm:text-xl">$25.00</button>
                    </div>
                    <div class="border-r px-2 py-1 sm:text-xl" style="border-color: #FCDD80;"><button class="mt-1">$35.00</button>
                    </div>
                    <div class="border-r px-2 py-1 sm:text-xl" style="border-color: #FCDD80;"><button class="mt-1">$50.00</button>
                    </div>
                    <div class="border-r px-2 py-1 sm:text-xl " style="border-color: #FCDD80;"><button
                            class="mt-1">$100.00</button></div>
                    <div class=" px-2 py-1 sm:text-xl "><button class="mt-1" style="border-color: #FCDD80;">Custom</button></div>
                </div>
                <NuxtLink class="block mt-3 text-blue-500">Add Promote Code</NuxtLink>


                <h1 class="text-xl mt-6 font-semibold">Your details</h1>

                <div class="border border-gray-300 rounded w-full p-2 mt-2">
                    <input type="name" placeholder="Name">
                </div>
                <div class="border border-gray-300 rounded w-full p-2 mt-4">
                    <input type="email" placeholder="Your Email">
                </div>

                <textarea name="message" id="" placeholder="Your Message (optional)"
                    class="border border-gray-300 rounded w-full p-2 h-24 mt-4"></textarea>

                <h1 class="text-xl mt-6 font-semibold">Delivery details</h1>

                <label class="inline-flex items-center gap-4 mt-2">
                    <input type="checkbox" v-model="isOn" class="sr-only peer">
                    <span class="text-sm text-gray-900">{{ isOn ? 'Send this card to myself' : 'option' }}</span>
                    <div
                        class="w-11 h-6 bg-gray-300 peer-checked:bg-green-500 rounded-full relative transition-all duration-300">
                        <div
                            class="absolute left-1 top-1 bg-white w-4 h-4 rounded-full transition peer-checked:translate-x-5">
                        </div>
                    </div>
                    
                </label>

                <div class="bg-orange-400 w-full rounded-full text-white text-center mt-6">
                    <button class="px-6 py-2 w-full">Checkout</button>
                </div>

            </div>
            <div class="flex gap-5">
                <div class="flex flex-col gap-5">

                    <img src="public/images/d1.png" alt="">
                    <img src="public/images/d2.png" alt="">
                    <img src="public/images/d3.png" alt="">
                    <img src="public/images/d4.png" alt="">
                </div>
                <div class="flex flex-col gap-5">

                    <img src="public/images/d5.png" alt="">
                    <img src="public/images/d6.png" alt="">
                    <img src="public/images/d7.png" alt="">
                    <img src="public/images/d8.png" alt="">
                </div>
                <div class="flex flex-col gap-5">

                    <img src="public/images/d9.png" alt="">
                    <img src="public/images/d10.png" alt="">
                    <img src="public/images/d11.png" alt="">
                    <img src="public/images/d12.png" alt="">
                </div>
            </div>
        </div>
    </section>
    </div>
</template>
<script setup>
const isOn = ref(false)
</script>