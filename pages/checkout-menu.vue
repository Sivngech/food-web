<template>
    <section>
        <div class="w-full h-[200px] md:h-[379px] overflow-hidden">
            <img src="public/images/resturant.png" alt="">
        </div>
    </section>

    <section class="w-full py-4 px-4">
        <div class="flex flex-col lg:flex-row justify-between gap-6">
            <div>
                <h1 class="text-[32px]">PokeBar Harbor Islands</h1>
                <div class="flex gap-2 mt-2">
                    <img src="public/images/Location-Icon.png" alt="">
                    <p class="text-[16px]">15 State Street, Suite 1100, Boston</p>
                    <NuxtLink to="#">Change Location</NuxtLink>
                </div>
                <div class="flex gap-2 mt-2">
                    <img src="public/images/Clock-Icon.png" alt="">
                    <p class="text-[16px]">Monday - Saturday 10:30 AM - 9:00 PM/ Sunday - 12:00 PM - 9:00 PM</p>
                </div>
            </div>

            <div class="flex gap-2 w-[187px] h-[44px] border rounded" style="border-color: #FCDD80;">
                <div class="border-r-1" style="border-color: #FCDD80; color:#765903;"><button
                        class="px-2 py-2">Delivery</button></div>
                <div style="color:#765903;"><button class="px-2 py-2">Pickup</button></div>
            </div>
        </div>
    </section>
    <section class="h-full w-[1440px] overflow-hidden">

        <h1 class="text-[24px] mb-20 h-[36px]">Menu</h1>
        <div class="mt-40">
            <div class="flex flex-row justify-center gap-10">
                <div class="overflow-hidden">
                    <div class=" w-[219px]   transform   justify-center">
                        <img class="absolute mb-10 h-[219px] w-[219px] object-cover top-180 left-37 z-10"
                            src="public/images/food1.png" alt="">
                    </div>
                    <div class=" w-[267px]  relative rounded shadow-md px-4 py-4 mb-40 shadow-gray-300 bg-white-300">
                        <div class="mt-16">
                            <h1 class="text-[18px] h-[28px]">Build Your Own Poke Bowl</h1>
                            <p class="w-[235px] text-[12px] h-[60px]">Extra proteins for an additional charge.</p>
                            <div class="flex gap-5">
                                <h1 class="text-[18px]">$20</h1>
                                <button class="rounded-full  text-white px-10 py-2  text-left  bg-gray-100"
                                    style="color:#F96540;">Add to cart</button>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="overflow-hidden">
                    <div class=" w-[219px]  transform   justify-center">
                        <img class="absolute mb-10 h-[219px] w-[219px] object-cover top-180 left-115"
                            src="public/images/food2.png" alt="">
                    </div>
                    <div class=" w-[267px]  relative rounded shadow-md px-4 py-4 mb-40 shadow-gray-300 bg-white-300">
                        <div class="mt-16">
                            <h1 class="text-[18px] h-[28px] w-[235px]">Rainbow Bowl</h1>
                            <p class="text-[12px] h-[60px]">Crab • Salmon* • Avocado • Cucumber •
                                Pineapple • Carrot • Sesame Seeds •
                                House Sauce</p>
                            <div class="flex gap-5">
                                <h1 class="text-[18px]">$10</h1>
                                <button class="rounded-full  text-white px-10 py-2  text-left  bg-gray-100"
                                    style="color:#F96540;">Add to cart</button>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="overflow-hidden">
                    <div class="w-[219px]   transform  justify-center">
                        <img class="absolute mb-10 h-[219px] w-[219px] object-cover top-180 left-185"
                            src="public/images/food3.png" alt="">
                    </div>
                    <div class=" w-[267px]  relative rounded shadow-md px-4 py-4 mb-40 shadow-gray-300 bg-white-300">
                        <div class="mt-16">
                            <h1 class="text-[18px] h-[28px] w-[235px]">Volcano Bowl</h1>
                            <p class="text-[12px] h-[60px]">Spicy Salmon* • Spicy Tuna* • Green Onion • Cabbage •
                                Cucumber • Carrot •
                                Jalapeno • Ginger</p>
                            <div class="flex gap-5">
                                <h1 class="text-[18px]">$12</h1>
                                <button class="rounded-full  text-white px-10 py-2  text-left  bg-gray-100"
                                    style="color:#F96540;">Add to cart</button>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="overflow-hidden">
                    <div class=" w-[219px]   transform   justify-center">
                        <img class="absolute mb-10 h-[219px] w-[219px] object-cover top-180 left-265 "
                            src="public/images/food4.png" alt="">
                    </div>
                    <div class="w-[267px]  relative rounded shadow-md px-4 py-4  bg-white-300 ">
                        <div class="mt-16">
                            <h1 class="text-[18px] h-[28px] w-[235px]">Tuna lover's Bowl</h1>
                            <p class="text-[12px] h-[60px]">Tuna* • Ground Spicy Tuna* • Avocado • Carrot •Cucumber •
                                Edamame • Watermelon • Radish </p>
                            <div class="flex gap-5">
                                <h1 class="text-[18px]">$18</h1>
                                <button class="rounded-full  text-white px-10 py-2  text-left  bg-gray-100"
                                    style="color:#F96540;">Add to cart</button>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>


        <div class="flex flex-row justify-center gap-10 mt-10">
            <div class="overflow-hidden">
                <div class=" w-[219px]   transform   justify-center">
                    <img class="absolute mb-10 h-[219px] w-[219px] object-cover top-280 left-37 z-10"
                        src="public/images/dish1.png" alt="">
                </div>
                <div class=" w-[267px]  relative rounded shadow-md px-4 py-4 mb-40 shadow-gray-300 bg-white-300">
                    <div class="mt-16">
                        <h1 class="text-[18px] h-[28px]">Dynamite Bowl</h1>
                        <p class="w-[235px] text-[12px] h-[60px]">Tuna* • Shrimp • Carrot • Mango • Jalapeno • Cucumber
                            • Chili Flakes • Sesame Seeds </p>
                        <div class="flex gap-5">
                            <h1 class="text-[18px]">$20</h1>
                            <button class="rounded-full  text-white px-10 py-2  text-left  bg-gray-100"
                                style="color:#F96540;">Add to cart</button>
                        </div>
                    </div>
                </div>
            </div>

            <div class="overflow-hidden">
                <div class=" w-[219px]  transform   justify-center">
                    <img class="absolute mb-10 h-[219px] w-[219px] object-cover top-280 left-115"
                        src="public/images/dish2.png" alt="">
                </div>
                <div class=" w-[267px]  relative rounded  px-4 py-4 mb-40 shadow-gray-300 bg-white-300"
                    style="box-shadow: 12px 14px 10px -4px rgba(0,0,0,0.55);">
                    <div class="mt-16">
                        <h1 class="text-[18px] h-[28px] w-[235px]">The Duke Bowl</h1>
                        <p class="text-[12px] h-[60px]">Tuna* • Salmon • Shrimp • Seaweed • Salad • Jalapeno • Sweet
                            Onion • Edamame • Cucumber</p>
                        <div class="flex gap-5">
                            <h1 class="text-[18px]">$16</h1>
                            <button class="rounded-full  text-white px-10 py-2  text-left  bg-gray-100"
                                style="color:#F96540;">Add to cart</button>

                        </div>

                    </div>

                </div>
            </div>


            <div class="overflow-hidden">
                <div class="w-[219px]   transform  justify-center">
                    <img class="absolute mb-10 h-[219px] w-[219px] object-cover top-280 left-190"
                        src="public/images/dish3.png" alt="">
                </div>
                <div class=" w-[267px]  relative rounded shadow-md px-4 py-4 mb-40 shadow-gray-300 bg-white-300">
                    <div class="mt-16">
                        <h1 class="text-[18px] h-[28px] w-[235px]">California Crunch Bowl</h1>
                        <p class="text-[12px] h-[60px]">Shrimp • Crab • Cucumber • Green Onion • Carrot • Edamame •
                            Avocado • Soy Sauce • Spicy Mayo Drizzle</p>
                        <div class="flex gap-5">
                            <h1 class="text-[18px]">$20</h1>
                            <button class="rounded-full  text-white px-10 py-2  text-left  bg-gray-100"
                                style="color:#F96540;">Add to cart</button>
                        </div>

                    </div>

                </div>
            </div>


            <div class="overflow-hidden">
                <div class=" w-[219px]   transform   justify-center">
                    <img class="absolute mb-10 h-[219px] w-[219px] object-cover top-280 left-265 "
                        src="public/images/dish4.png" alt="">
                </div>
                <div class="w-[267px]  relative rounded shadow-md px-4 py-4  bg-white-300 ">
                    <div class="mt-16">
                        <h1 class="text-[18px] h-[28px] w-[235px]">Salmon Bowl</h1>
                        <p class="text-[12px] h-[60px]">Spicy Salmon* • Green Onion • Avocado • Cucumber • House Sauce
                            mixed with light sriracha • Lemon </p>
                        <div class="flex gap-5">
                            <h1 class="text-[18px]">$15</h1>
                            <button class="rounded-full  text-white px-10 py-2  text-left  bg-gray-100"
                                style="color:#F96540;">Add to cart</button>
                        </div>

                    </div>

                </div>
            </div>

        </div>

        <h1 class="text-[24px] top-300">Drink</h1>


        <div class="flex flex-row justify-center gap-10 mt-20">
            <div class="overflow-hidden">
                <div class=" w-[219px]   transform   justify-center">
                    <img class="absolute mb-10 h-[219px] w-[219px] object-cover top-410 left-37 z-10"
                        src="public/images/drink1.png" alt="">
                </div>
                <div class=" w-[267px]  relative rounded shadow-md px-4 py-4 mb-40 shadow-gray-300 bg-white-300">
                    <div class="mt-16">
                        <h1 class="text-[18px] h-[28px]">Coca Cola</h1>

                        <div class="flex gap-5">
                            <h1 class="text-[18px]">$2</h1>
                            <button class="rounded-full  text-white px-10 py-2  text-left  bg-gray-100"
                                style="color:#F96540;">Add to cart</button>
                        </div>


                    </div>

                </div>
            </div>

            <div class="overflow-hidden">
                <div class=" w-[219px]  transform   justify-center">
                    <img class="absolute mb-10 h-[219px] w-[219px] object-cover top-410 left-115"
                        src="public/images/drink2.png" alt="">
                </div>
                <div class=" w-[267px]  relative rounded  px-4 py-4 mb-40 shadow-gray-300 bg-white-300"
                    style="box-shadow: 12px 14px 10px -4px rgba(0,0,0,0.55);">
                    <div class="mt-16">
                        <h1 class="text-[18px] h-[28px] w-[235px]">Water</h1>

                        <div class="flex gap-5">
                            <h1 class="text-[18px]">$2</h1>
                            <button class="rounded-full  text-white px-10 py-2  text-left  bg-gray-100"
                                style="color:#F96540;">Add to cart</button>
                        </div>
                    </div>

                </div>
            </div>


            <div class="overflow-hidden">
                <div class="w-[219px]   transform  justify-center">
                    <img class="absolute mb-10 h-[219px] w-[219px] object-cover top-410 left-190"
                        src="public/images/drink3.png" alt="">
                </div>
                <div class=" w-[267px]  relative rounded shadow-md px-4 py-4 mb-40 shadow-gray-300 bg-white-300">
                    <div class="mt-16">
                        <h1 class="text-[18px] h-[28px] w-[235px]">Sweet Tea</h1>
                        <div class="flex gap-5">
                            <h1 class="text-[18px]">$2</h1>
                            <button class="rounded-full  text-white px-10 py-2  text-left  bg-gray-100"
                                style="color:#F96540;">Add to cart</button>
                        </div>

                    </div>

                </div>
            </div>


            <div class="overflow-hidden">
                <div class=" w-[219px]   transform   justify-center">
                    <img class="absolute mb-10 h-[219px] w-[219px] object-cover top-410 left-265 "
                        src="public/images/drink4.png" alt="">
                </div>
                <div class="w-[267px]  relative rounded shadow-md px-4 py-4  bg-white-300 ">
                    <div class="mt-16">
                        <h1 class="text-[18px] h-[28px] w-[235px]">Lemonade</h1>

                        <div class="flex gap-5">
                            <h1 class="text-[18px]">$2</h1>
                            <button class="rounded-full  text-white px-10 py-2  text-left  bg-gray-100"
                                style="color:#F96540;">Add to cart</button>
                        </div>

                    </div>

                </div>
            </div>

        </div>


    </section>

</template>
