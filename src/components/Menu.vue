<script setup lang="ts">
defineProps({
  name: String
});
</script>

<template>
  <div class="flex justify-center bg-amber-100 ml-12 mr-12">
    <div class="inline-flex justify-center w-4/5">
      <div class="inline-flex gap-10 justify-start">
        <a href="#"><p>Главная</p></a>
        <a href="#"><p>Новые</p></a>
        <a href="#"><p>Мои запросы</p></a>
      </div>
      <div class="w-1/2 flex justify-end">
        <a href="#">
          <div class="inline-flex gap-4">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTkthDzK4If2hjtRw9Qq02RtMYOtHvQ3bNtug&s"
                 alt="avatar" class="w-8 h-8 rounded-full">
            <p>{{ name }}</p>
          </div>
        </a>
      </div>
    </div>
  </div>
</template>

<style scoped>

</style>