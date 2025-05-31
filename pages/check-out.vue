<template>
    <section class="px-4 py-6">
        <div class="flex flex-col md:flex-row items-center justify-center gap-10">
            <div class="flex flex-col items-center md:items-start w-full md:w-1/2 space-y-4">
                 

            <div class="flex gap-2 w-full max-w-xs h-[44px] border rounded border-[#FCDD80]">
          <button class="px-4 py-2 w-1/2 text-[#765903] border-r border-[#FCDD80]">Delivery</button>
          <button class="px-4 py-2 w-1/2 text-[#765903]">Pickup</button>
        </div>

            <label for="find" class="text-sm text-gray-600 text-center md:text-left">
                Find nearby locations to order from
            </label>

              <div class="flex items-center border border-gray-300 rounded w-full max-w-md p-2">
          <img src="public/images/Search-Icon.png" alt="Search" class="w-4 h-4 mr-2" />
          <input
            type="text"
            id="find"
            placeholder="Find a store near you"
            class="w-full outline-none text-base placeholder:text-sm"
          />
        </div>
           
            <img class="w-full max-w-md h-auto mt-4" src="public/images/Container.png" alt="">
            </div>

            <div class="w-full md:w-1/2 flex justify-center">
                <img class="w-full max-w-lg h-auto mt-4 md:mt-0" src="public/images/Map.png" alt="">
            </div>
           
            

        </div>

    </section>

</template>