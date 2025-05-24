<template>
    <section class="w-full h-full">
        
        <div class="flex gap-5 ">
            <div class="bg-white shadow-md w-[796px] h-[228px]">
                <h1 class="text-[16px] font-bold" style="color: #171A1F;">Order summary</h1>

                <table class=" w-[748px] mt-2 shadow" style="border-left: none; border-right: none;">
                    <tr>
                        <td>
                            <img src="public/images/im1.png" alt="" class="w-[62px] p-2">
                        </td>
                        <td>
                            <div class="w-[304px] ml-5">
                                <p class="text-[16px]">Build Your Own Poke Bowl</p>
                                <p class="text-[12px]" style="color: #565E6C;">Tuna* • Ground Spicy Tuna* • Avocado...
                                </p>
                            </div>
                        </td>
                        <td>
                            <p class="left-4 text-[16px]">$25</p>
                        </td>
                        <td><img class="left-4" src="public/images/pen.png" alt=""></td>
                        <td><img src="public/images/trash.png" alt=""></td>

                    </tr>

                </table>


                <table class="shadow mt-4 w-[748px]" style="border-right: none;border-left: none;">
                    <tr>
                        <td>
                            <img src="public/images/im2.png" alt="" class="w-[62px] p-2">
                        </td>
                        <td>
                            <div class="w-[304px] ml-5">
                                <p class="text-[16px]">California Crunch Bowl</p>
                                <p class="text-[12px]" style="color: #565E6C;">Shrimp • Crab • Cucumber • Green Onio....
                                </p>
                            </div>
                        </td>
                        <td>
                            <p class="left-4 text-[16px]">$9</p>
                        </td>
                        <td><img class="left-4" src="public/images/pen.png" alt=""></td>
                        <td><img src="public/images/trash.png" alt=""></td>
                    </tr>

                </table>
            </div>


            <div class="w-[348px] shadow p-4">
                <div>Payment method</div>
                <a href="#">
                    <p style="color:#379AE6;">Change payment methods</p>
                </a>


                <div class="border rounded px-2 py-2" style="border-color: #97DB32; background-color: #F5FCEB;">
                    <table class="p-2">
                        <tr>
                            <td>
                                <img src="public/images/Image174.png" alt="" class="ml-2">
                            </td>
                            <td>
                                <p class="ml-4">Mastercard</p>
                            </td>
                            <td>
                                <p class="ml-4">**** 5987</p>
                            </td>
                        </tr>
                    </table>
                </div>


                <div>
                    <h1>Voucher</h1>

                    <div class="flex gap-4">
                        <div class="border rounded" style="border-color: #9095A0;">
                            <input type="text" placeholder="input" class="px-2 py-2">
                        </div>
                        <div class="border rounded" style="color:#765903; background-color: #FEF9EB;">
                            <button class="px-2 py-2">Apply</button>
                        </div>
                    </div>
                    <div style="color: #765903;" class="bg-yellow-300 w-[60px] mt-2 rounded-full">
                        <p>freeship</p>
                    </div>

                    <div>Summary</div>

                    <table>
                        <tr>
                            <td>
                                <p class="text-[12px]">Subtotal</p>
                            </td>
                            <td>
                                <p class="ml-50">$34</p>
                            </td>
                        </tr>
                        <tr>
                            <div>
                                <td>
                                    <p class="text-[12px]">Ship</p>
                                </td>
                                <td>
                                    <p class="ml-50">$0</p>
                                </td>
                            </div>
                        </tr>

                        <tr>
                            <div>
                                <td>
                                    <p class="text-[12px]">Fee</p>
                                </td>
                                <td>
                                    <p class="ml-50">$0</p>
                                </td>
                            </div>
                        </tr>
                    </table>

                    <table class="border w-[280px]"
                        style="border-left: none;border-right: none; border-color:gray ; border-bottom: none;">
                        <tr>
                            <td>
                                <p class="text-[12px]">Total</p>
                            </td>
                            <td>
                                <p class="ml-50 text-[18px]" style="color: #F96540;">$34</p>
                            </td>
                        </tr>
                    </table>

                </div>

                <div class="rounded-full text-white text-center " style="background-color: #F96540;"> 
                    <button class="px-2 py-2 ">Proceed to payment</button>
                </div>

            </div>

        </div>
        

        <h1 class="text-[24px] mb-40">You might also like</h1>
 <div class="flex flex-row justify-center gap-10 mt-10">
            <div class="overflow-hidden">
                <div class=" w-[219px]   transform   justify-center">
                    <img class="absolute mb-10 h-[219px] w-[219px] object-cover top-130 left-37 z-10"
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
                    <img class="absolute mb-10 h-[219px] w-[219px] object-cover top-130 left-115"
                        src="public/images/dish2.png" alt="">
                </div>
                <div class=" w-[267px] shadow  relative rounded  px-4 py-4 mb-40 shadow-gray-300 bg-white-300">
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
                    <img class="absolute mb-10 h-[219px] w-[219px] object-cover top-130 left-190"
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
                    <img class="absolute mb-10 h-[219px] w-[219px] object-cover top-130 left-265 "
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


    </section>




</template>
