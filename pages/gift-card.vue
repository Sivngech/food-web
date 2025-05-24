<template>
    <section>
        <div class="flex gap-10">
            <div>
                <h1 class="text-[48px]">Give the Perfect Gift</h1>
                <p>Get a voucher for yourself or gift one to a friend</p>
                <p class="text-[20px] mt-5">What kind of gift is it?</p>
                <div class="mt-2 flex gap-5">
                    <div class="flex w-[280px] border rounded h-[102px] items-center gap-5"
                        style="border-color: #F96540;color:#171A1F;">
                        <img src="public/images/Gift-Icon.png" alt="" class="w-[36px] ml-4 mb-5">
                        <div class="flex flex-col">
                            <h1 class="text-[18px]">For one individual</h1>
                            <p class="text-[12px] ">Send a gift card to one recipient</p>
                        </div>
                    </div>
                    <div class="flex w-[280px] border rounded h-[102px] items-center gap-5"
                        style="border-color: #BCC1CA;color:#171A1F;">
                        <img src="public/images/Diversity-Icon.png" alt="" class="w-[36px]  ml-4 mb-5">
                        <div class="flex flex-col">
                            <h1 class="text-[18px]">Group gift card</h1>
                            <p class="text-[12px]">Pool money from multiple contributors for one recipient</p>
                        </div>
                    </div>
                </div>

                <h1 class="text-[20px] w-[167px]">eGift card amount</h1>
                <div class="border flex h-[36px] w-[396px] ml-2 gap-3 rounded" style="border-color: #FCDD80;">
                    <div class="border-r-1 w-[78px]" style="border-color: #FCDD80;"><button class="mt-1">$25.00</button>
                    </div>
                    <div class="border-r-1 w-[78px]" style="border-color: #FCDD80;"><button class="mt-1">$35.00</button>
                    </div>
                    <div class="border-r-1 w-[78px]" style="border-color: #FCDD80;"><button class="mt-1">$50.00</button>
                    </div>
                    <div class="border-r-1 w-[78px] " style="border-color: #FCDD80;"><button
                            class="mt-1">$100.00</button></div>
                    <div><button class="w-[78px]  mt-1 mr-2">Custom</button></div>
                </div>
                <NuxtLink to="add-promote-code" style="color: #379AE6;">Add Promote Code</NuxtLink>


                <h1 class="text-[20px]">Your details</h1>

                <div class="border border-gray-300 rounded w-[395px] p-1">
                    <input type="name" placeholder="Name">
                </div>
                <div class="border border-gray-300 rounded w-[395px] p-1 mt-4 mb-4">
                    <input type="email" placeholder="Your Email">
                </div>

                <textarea name="message" id="" placeholder="Your Message (optional)"
                    class="w-[395px] h-[94px] border border-gray-300 rounded"></textarea>

                <h1 class="text-[20px]">Delivery details</h1>

                <label class="inline-flex items-center cursor-pointer gap-10">
                    <input type="checkbox" v-model="isOn" class="sr-only peer">
                    <span class="ml-3 text-sm font-medium text-gray-900">{{ isOn ? 'Send this card to myself' : 'option' }}</span>
                    <div
                        class="w-11 h-6 bg-gray-300 peer-checked:bg-green-500 rounded-full relative transition-all duration-300">
                        <div
                            class="absolute left-1 top-1 bg-white w-4 h-4 rounded-full transition peer-checked:translate-x-5">
                        </div>
                    </div>
                    
                </label>

                <div class="bg-orange-400 w-[396px] rounded-full text-white text-center mt-4">
                    <button class="px-4 py-2">Checkout</button>
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
</template>
<script setup>
const isOn = ref(false)
</script>