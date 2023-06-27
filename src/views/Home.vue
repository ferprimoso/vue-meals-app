<template>
    <div class="flex p-8 justify-center">
        <input type="text" class="rounded border-2 border-gray-200 w-full place" placeholder="Search for Meals">
    </div>

    <div class="flex gap-1">
        
    </div>
</template>

<script setup>
import { computed } from 'vue';



const meals = computed(() => store.state.meals)



</script>