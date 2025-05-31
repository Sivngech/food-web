<template>
  <div class="fixed inset-0 z-50 flex items-center justify-center bg-white bg-opacity-30 px-4 overflow-hidden">
    <div class="bg-white rounded-lg shadow-lg w-full max-w-5xl flex overflow-hidden">
      
      
      <div class="w-full md:w-1/2 p-8">
        <h1 class="text-2xl font-semibold mb-2">Reservation</h1>
        <p class="text-gray-600 text-sm mb-6">
          We provide a convenient online reservation system. Simply select your desired date, time, and party size, and we will make sure that your table is ready upon your arrival.
        </p>

        
        <div class="mb-4">
          <label class="block text-sm mb-1">Your Name</label>
          <input type="text" placeholder="Your name" class="w-full border border-gray-400 rounded px-3 py-2 focus:outline-none focus:ring-2 sm:text-sm md:text-lg">
        </div>

       
        <div class="flex gap-4 mb-4">
          <div class="w-1/2">
            <label class="block text-sm mb-1">Guests</label>
            <div class="relative">
              <input type="text" placeholder="Number of guest" class="w-full border border-gray-400 rounded px-3 py-2 pr-8 focus:outline-none sm:text-sm md:text-lg">
              <img src="public/images/Chevron down large.png" alt="" class="absolute right-2 top-2.5 w-4 h-4 pointer-events-none ">
            </div>
          </div>
          <div class="w-1/2">
            <label class="block text-sm mb-1">Restaurant</label>
            <div class="relative">
              <input type="text" placeholder="Your favorite place?" class="w-full border border-gray-400 rounded px-3 py-2 pr-8 focus:outline- sm:text-sm md:text-lg">
              <img src="public/images/Chevron down large.png" alt="" class="absolute right-2 top-2.5 w-4 h-4 pointer-events-none">
            </div>
          </div>
        </div>

      
        <div class="flex gap-4 mb-6">
          <div class="w-1/2">
            <label class="block text-sm mb-1">Date</label>
            <div class="relative">
              <input type="text" placeholder="Fri 25, Sep" class="w-full border border-gray-400 rounded px-3 py-2 pr-8 focus:outline-none sm:text-sm md:text-lg">
              <img src="public/images/Chevron down large.png" alt="" class="absolute right-2 top-2.5 w-4 h-4 pointer-events-none">
            </div>
          </div>
          <div class="w-1/2">
            <label class="block text-sm mb-1">Time</label>
            <div class="relative">
              <input type="text" placeholder="6:00 PM" class="w-full border border-gray-400 rounded px-3 py-2 pr-8 focus:outline-none sm:text-sm md:text-lg">
              <img src="public/images/Chevron down large.png" alt="" class="absolute right-2 top-2.5 w-4 h-4 pointer-events-none">
            </div>
          </div>
        </div>

        
        <button class="w-full bg-[#F96540] hover:bg-[#e4562f] text-white text-sm py-3 rounded-full transition">
          Book a table
        </button>
      </div>

      
      <div class="hidden md:block md:w-1/2 relative">
        <img src="public/images/right-image.png" alt="Reservation Bowl" class="h-full w-full object-cover">
         <div class="absolute left-110 top-3">
                    <img src="public/images/Eremove2.png" alt="" class="w-[32px] h-[32px]">
                </div>
      </div>
    </div>
  </div>
</template>
