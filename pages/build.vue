<template>
  <div class="fixed inset-0 z-50 flex items-center justify-center bg-black bg-opacity-50">
    <div class="bg-white rounded-2xl shadow-lg w-full max-w-lg p-6 relative">
     
      <button class="absolute top-4 right-4 text-gray-500 hover:text-gray-800" @click="$emit('close')">
        ✕
      </button>

      
      <div class="flex items-center space-x-4 mb-4">
        <img src="public/images/picture.png" alt="Poke Bowl" class="w-16 h-16 rounded-full object-cover" />
        <div>
          <h2 class="text-xl font-semibold">Build Your Own Poke Bowl</h2>
          <p class="text-sm text-gray-500">Extra proteins for an additional charge.</p>
        </div>
      </div>

     
      <div class="mb-4">
        <h3 class="text-sm font-bold text-gray-700">Step 1</h3>
        <p class="font-semibold text-gray-900 mb-2">Choose a Base</p>

        <div class="space-y-2">
          <label v-for="option in baseOptions" :key="option" class="flex items-center space-x-2">
            <input type="radio" v-model="selectedBase" :value="option" class="accent-red-500" />
            <span>{{ option }}</span>
          </label>
        </div>
      </div>

     
      <div class="flex items-center space-x-2 mt-4">
        <button @click="decrease" class="w-8 h-8 bg-gray-200 rounded hover:bg-gray-300">−</button>
        <span>{{ quantity }}</span>
        <button @click="increase" class="w-8 h-8 bg-red-500 text-white rounded hover:bg-red-600">+</button>
      </div>

      
      <div class="mt-6">
        <button
          class="w-full py-2 bg-green-500 text-white rounded hover:bg-green-600 transition"
          @click="addToCart"
        >
          Add to cart $20
        </button>
      </div>
    </div>
  </div>
</template>

<script setup>
import { ref } from 'vue'

const baseOptions = [
  'White Rice',
  'Brown Rice',
  'Salad',
  'Noodles',
  'Half and Half (White Rice and Brown Rice)',
  'Half and Half (White Rice and Salad)',
  'Half and Half (Brown Rice and Salad)',
  'Half and Half (Noodles and Salad)'
]

const selectedBase = ref('White Rice')
const quantity = ref(1)

const increase = () => {
  quantity.value++
}

const decrease = () => {
  if (quantity.value > 1) quantity.value--
}

const addToCart = () => {
  alert(`Added ${quantity.value} Poke Bowl(s) with ${selectedBase.value} to cart.`)
}
</script>
