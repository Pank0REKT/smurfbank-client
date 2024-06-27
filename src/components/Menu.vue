<script setup lang="ts">
defineProps({
  name: String
});
</script>

<template>
  <div class="flex justify-center bg-amber-100 ml-12 mr-12">
    <div class="inline-flex justify-center gap-10 w-4/5">
      <a href="#"><p>Главная</p></a>
      <a href="#"><p>Новые</p></a>
      <a href="#"><p>Мои запросы</p></a>
      <div class="w-2/5 flex justify-end">
        <a href="#"><p>{{ name }}</p></a>
      </div>
    </div>
  </div>
</template>

<style scoped>

</style>