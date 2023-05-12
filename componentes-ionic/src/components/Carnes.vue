<template>
    <h2 class="text-2xl font-semibold
    mb-5">
        Esta es la seccion de carnes
    </h2>
    <div class="flex flex-wrap gap-3">
        <div class="bg-cyan-100 p-1 rounded-lg w-1/3
        transition ease-in-out duration-100
        hover:shadow-lg hover:bg-cyan-300 hover:cursor-pointer">
            <h3 class="text-md font-semibold italic">
                Carne de res
            </h3>
            <p class="text-justify">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur alias quos veritatis minus non! Nobis veniam velit quaerat, earum, fuga placeat quod minima ducimus facere, quisquam labore corporis excepturi ullam?
            </p>
        </div>
        <div class="bg-cyan-100 p-1 rounded-lg w-1/3
        hover:animate-bounce">
            <h3 class="text-md font-semibold italic">
                Carne de cerdo
            </h3>
            <p class="text-justify">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur alias quos veritatis minus non! Nobis veniam velit quaerat, earum, fuga placeat quod minima ducimus facere, quisquam labore corporis excepturi ullam?
            </p>
        </div>
        <div class="bg-cyan-100 p-1 rounded-lg w-1/3
        hover:animate-pulse">
            <h3 class="text-md font-semibold italic">
                Carne de pollo
            </h3>
            <p class="text-justify">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur alias quos veritatis minus non! Nobis veniam velit quaerat, earum, fuga placeat quod minima ducimus facere, quisquam labore corporis excepturi ullam?
            </p>
        </div>
    </div>
</template>
<script lang="ts">
import { Vue } from 'vue-class-component'
export default class Carnes extends Vue { }
</script>