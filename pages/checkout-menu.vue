<template>
  <section>
    <div class="w-full h-[200px] md:h-[379px] overflow-hidden">
      <img src="public/images/resturant.png" alt="" class="w-full h-full object-cover" />
    </div>
  </section>
  <section class="w-full py-4 px-4">
    <div class="flex flex-col lg:flex-row justify-between gap-6">
      <div>
        <h1 class="text-lg font-semibold">PokeBar Harbor Islands</h1>
        <div class="flex flex-wrap gap-2 mt-2 items-center">
          <img src="public/images/Location-Icon.png" alt="" class="w-5 h-5" />
          <p class="text-sm">15 State Street, Suite 1100, Boston</p>
          <NuxtLink to="#" class="text-blue-500 text-sm">Change Location</NuxtLink>
        </div>
        <div class="flex flex-wrap gap-2 mt-2 items-center">
          <img src="public/images/Clock-Icon.png" alt="" class="w-5 h-5" />
          <p class="text-sm">Monday - Saturday 10:30 AM - 9:00 PM / Sunday - 12:00 PM - 9:00 PM</p>
        </div>
      </div>

      <div class="flex gap-2 w-full sm:w-[187px] h-[44px] border rounded border-yellow-300 text-yellow-900">
        <button class="w-1/2 border-r border-yellow-300 px-2 py-2">Delivery</button>
        <button class="w-1/2 px-2 py-2">Pickup</button>
      </div>
    </div>
  </section>

  <section class="px-4">
    <h1 class="text-2xl mb-8">Menu</h1>

    <div class="grid gap-10 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 bg-white p-4 relative">
      <div v-for="(item, index) in menuItems" :key="index" class="relative min-h-64 s-dow">
        <img :src="item.image" alt="images"
          class="absolute w-[219px] h-[219px] top-0 mx-auto inset-0 z-10 transform object-cover" />
        <div class="mt-4 p-4 rounded-xl  bg-white min-h-64 justify-between">
          <h1 class="text-lg font-semibold mt-44">{{ item.name }}</h1>
          <p class="text-sm my-2">{{ item.description }}</p>
          <div class="flex items-center justify-between">
            <span class="text-lg">${{ item.price }}</span>
            <button class="rounded-full text-white px-4 py-1 bg-orange-500">Add to cart</button>
          </div>
        </div>
      </div>
    </div>

    <h1 class="text-2xl mt-12 mb-8">Drink</h1>

    <div class="grid gap-10 md:grid-cols-2 lg:grid-cols-4 relative p-3">
      <div v-for="(drink, index) in drinks" :key="index" class="relative" style="
box-shadow: 7px 7px 1px -5px rgba(0,0,0,0.18); border-radius: 5%;">
        <img :src="drink.image" alt="" class="w-[219px] h-[219px] object-cover mx-auto absolute top-0 inset-0 z-10" />
        <div class="mt-4 p-4 rounded shadow-gray-500 shadow-md bg-white">
          <h1 class="text-lg font-semibold mt-44">{{ drink.name }}</h1>
          <div class="flex items-center justify-between mt-2">
            <span class="text-lg">${{ drink.price }}</span>
            <button class="rounded-full text-white px-4 py-1 bg-orange-500">Add to cart</button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script setup>
const menuItems = [
  {
    name: 'Build Your Own Poke Bowl',
    description: 'Extra proteins for an additional charge.',
    price: 20,
    image: '/images/food1.png',
  },
  {
    name: 'Rainbow Bowl',
    description: 'Crab • Salmon* • Avocado • Cucumber • Pineapple • Carrot • Sesame Seeds • House Sauce',
    price: 10,
    image: '/images/food2.png',
  },
  {
    name: 'Volcano Bowl',
    description: 'Spicy Salmon* • Spicy Tuna* • Green Onion • Cabbage • Cucumber • Carrot • Jalapeno • Ginger',
    price: 12,
    image: '/images/food3.png',
  },
  {
    name: "Tuna lover's Bowl",
    description: 'Tuna* • Ground Spicy Tuna* • Avocado • Carrot • Cucumber • Edamame • Watermelon • Radish',
    price: 18,
    image: '/images/food4.png',
  },
  {
    name: 'Dynamite Bowl',
    description: 'Tuna* • Shrimp • Carrot • Mango • Jalapeno • Cucumber • Chili Flakes • Sesame Seeds',
    price: 20,
    image: '/images/dish1.png',
  },
  {
    name: 'The Duke Bowl',
    description: 'Tuna* • Salmon • Shrimp • Seaweed • Salad • Jalapeno • Sweet Onion • Edamame • Cucumber',
    price: 16,
    image: '/images/dish2.png',
  },
  {
    name: 'California Crunch Bowl',
    description: 'Shrimp • Crab • Cucumber • Green Onion • Carrot • Edamame • Avocado • Soy Sauce • Spicy Mayo Drizzle',
    price: 20,
    image: '/images/dish3.png',
  },
  {
    name: 'Salmon Bowl',
    description: 'Spicy Salmon* • Green Onion • Avocado • Cucumber • House Sauce with light sriracha • Lemon',
    price: 15,
    image: '/images/dish4.png',
  },
];

const drinks = [
  { name: 'Coca Cola', price: 2, image: '/images/drink1.png' },
  { name: 'Water', price: 2, image: '/images/drink2.png' },
  { name: 'Sweet Tea', price: 2, image: '/images/drink3.png' },
  { name: 'Lemonade', price: 2, image: '/images/drink4.png' },
];
</script>
<style>
.s-dow {
  box-shadow: 7px 7px 1px -5px rgba(0, 0, 0, 0.18);
  border-radius: 5%;
}
</style>
