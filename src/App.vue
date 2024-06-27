<script setup lang="ts">
import Menu from "@/components/Menu.vue";
import PlayersGrid from "./components/Grids/PlayersGrid.vue";

const players = [
  {
    id: 1,
    name: 'Earthen Bottle',
    rating: 7,
    reason: '$48',
  },
  {
    id: 2,
    name: 'Earthen Bottle',
    rating: 9,
    reason: '$48',
  },
  {
    id: 3,
    name: 'Earthen Bottle',
    rating: 9,
    reason: '$48',
  },
  {
    id: 4,
    name: 'Earthen Bottle',
    rating: 10,
    reason: '$48',

  }]
</script>

<template>
  <div class="w-full mt-4">
    <Menu name="Имя"/>
    <PlayersGrid :players="players"/>
  </div>
</template>
