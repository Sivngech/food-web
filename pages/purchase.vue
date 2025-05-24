<template>
  <section class="flex flex-col items-center justify-center min-h-screen bg-white px-4 py-8">
    
   
    <div class="relative">
      <img src="public/images/profile.png" class="w-[160px] h-[160px] rounded-full" alt="Profile Image">
      <img src="public/images/square check.png" class="absolute bottom-5 right-0 w-6 h-6" alt="Check">
    </div>

  
    <p class="text-[28px] font-semibold mt-6">Thank you for your purchase!</p>
    <p class="text-[14px] text-gray-500 mt-1">Food is on its way to you</p>

    
    <div class="mt-6 bg-white shadow-md rounded-xl w-full max-w-xl px-6 py-6">
      
     
      <div class="space-y-4">
       
        <div class="flex justify-between items-center border-b pb-2" style="border-color: #DEE1E6;">
          <div class="flex items-center gap-2 text-gray-500">
            <img src="public/images/Calendar date 1.png" alt="" class="w-5">
            <span class="text-[14px]">Date</span>
          </div>
          <span class="text-[14px]">27/04/2023</span>
        </div>

        
        <div class="flex justify-between items-center border-b pb-2" style="border-color: #DEE1E6;">
          <div class="flex items-center gap-2 text-gray-500">
            <img src="public/images/Profile 1.png" alt="" class="w-5">
            <span class="text-[14px]">Customer</span>
          </div>
          <span class="text-[14px] font-semibold text-black">John Miller</span>
        </div>

       
        <div class="flex justify-between items-center border-b pb-2" style="border-color: #DEE1E6;">
          <div class="flex items-center gap-2 text-gray-500">
            <img src="public/images/Money 13 1.png" alt="" class="w-5">
            <span class="text-[14px]">Payment Method</span>
          </div>
          <img class="w-[35px]" src="public/images/Image174.png" alt="Payment">
        </div>

        
        <div class="flex justify-between items-center border-b pb-2" style="border-color: #DEE1E6;">
          <div class="flex items-center gap-2 text-gray-500">
            <img src="public/images/Receipt list 43 1.png" alt="" class="w-5">
            <span class="text-[14px]">Order Number</span>
          </div>
          <span class="text-[14px]">586789963</span>
        </div>

       
        <div class="flex justify-between items-center">
          <div class="flex items-center gap-2 text-gray-500">
            <img src="public/images/Currency dollar 1.png" alt="" class="w-5">
            <span class="text-[14px]">Total</span>
          </div>
          <span class="text-[14px]">$34</span>
        </div>
      </div>

     
      <h2 class="mt-6 mb-2 text-[16px] font-semibold">Order Line</h2>

    
      <div class="flex justify-between items-start mb-4">
        <img src="public/images/im1.png" alt="" class="w-[64px] h-[64px] object-cover rounded-lg">
        <div class="flex-1 mx-4">
          <p class="text-[14px] font-semibold">Build Your Own Poke Bowl</p>
          <p class="text-[12px] text-gray-500">Tuna • Ground Spicy Tuna • Avocado...</p>
        </div>
        <div class="text-center">
          <div class="bg-gray-200 rounded-full w-8 h-8 flex items-center justify-center text-[12px]">x1</div>
          <p class="text-[14px] mt-1">$25</p>
        </div>
      </div>

    
      <div class="flex justify-between items-start">
        <img src="public/images/im2.png" alt="" class="w-[64px] h-[64px] object-cover rounded-lg">
        <div class="flex-1 mx-4">
          <p class="text-[14px] font-semibold">California Crunch Bowl</p>
          <p class="text-[12px] text-gray-500">Shrimp • Crab • Cucumber • Green Onion...</p>
        </div>
        <div class="text-center">
          <div class="bg-gray-200 rounded-full w-8 h-8 flex items-center justify-center text-[12px]">x1</div>
          <p class="text-[14px] mt-1">$9</p>
        </div>
      </div>

      <div class="mt-6 flex justify-center">
        <button class="bg-[#F96540] text-white px-6 py-2 rounded-full text-[14px] hover:bg-[#e45733] transition">
          Back to home
        </button>
      </div>
    </div>

   
    <p class="mt-6 text-[14px] text-gray-700">How was your experience?</p>
    <img src="public/images/Rating (1).png" alt="Rating" class="mt-2 w-32">
  
  </section>
</template>
