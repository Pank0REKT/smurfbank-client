<script setup lang="ts">
defineProps({
  id: Number,
  name: String,
  rating: Number,
  reason: String
})
</script>

<template>
  <div class="group">
    <div class="aspect-h-1 aspect-w-1 w-full overflow-hidden rounded-lg bg-gray-200 xl:aspect-h-8 xl:aspect-w-7">
      <img alt="profile_img" src="https://s6.stc.all.kpcdn.net/expert/wp-content/uploads/2022/01/shutterstock_2000063207-960x540.jpg"
           class="h-full w-full object-cover object-center group-hover:opacity-75"/>
    </div>
    <h3 class="mt-4 text-sm text-gray-700">{{ name }}</h3>
    <p class="mt-1 text-lg font-medium text-gray-900">Рейтинг: {{ rating }}. {{ reason }}</p>
  </div>
</template>