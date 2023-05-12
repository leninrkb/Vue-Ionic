<template>
  <header class="w-fit mx-auto
    text-3xl font-semibold font-sans mt-10 mb-10
    shadow-lg rounded-lg p-3
    transition ease-in-out duration-500
    hover:bg-amber-500 hover:text-gray-100
    hover:shadow-amber-500">
    Cosas que no puedo comer :(
  </header>
  <nav class="container mx-auto
  bg-cyan-500 p-1 rounded-lg
  text-gray-100 text-lg font-semibold">
    <ul class="flex gap-5">
      <li @click="navegar('carnes')" class="p-2 rounded-lg
      transition ease-in-out duration-300 
      hover:-translate-y-1
      hover:underline underline-offset-4
      hover:shadow-lg
      cursor-pointer">Carnes</li>
      <li class="p-2 rounded-lg
      transition ease-in-out duration-300 
      hover:-translate-y-1
      hover:underline underline-offset-4
      hover:shadow-lg
      cursor-pointer">Liquidos</li>
      <li class="p-2 rounded-lg
      transition ease-in-out duration-300 
      hover:-translate-y-1
      hover:underline underline-offset-4
      hover:shadow-lg
      cursor-pointer">Harinas</li>
    </ul>
  </nav>
  <div class="container mx-auto">
    <div class="h-1 bg-cyan-500 my-1 rounded-full"></div>
    <div class="">
      <router-view></router-view>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
export default defineComponent({
  methods: {
    navegar(path:string){
      this.$router.push(path)
    }
  },
})
</script>
