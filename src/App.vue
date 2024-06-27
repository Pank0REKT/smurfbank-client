<script setup lang="ts">
import Menu from "@/components/Menu.vue";
import PlayersGrid from "./components/Grids/PlayersGrid.vue";

const players = [
  {
    id: 1,
    name: 'Earthen Bottle',
    rating: Math.floor(Math.random() * (10-1 + 1)) + 1,
    reason: '$48',
  },
  {
    id: 2,
    name: 'Earthen Bottle',
    rating: Math.floor(Math.random() * (10-1 + 1)) + 1,
    reason: '$48',
  },
  {
    id: 3,
    name: 'Earthen Bottle',
    rating: Math.floor(Math.random() * (10-1 + 1)) + 1,
    reason: '$48',
  },
  {
    id: 4,
    name: 'Earthen Bottle',
    rating: Math.floor(Math.random() * (10-1 + 1)) + 1,
    reason: '$48',

  },
  {
    id: 5,
    name: 'Earthen Bottle',
    rating: Math.floor(Math.random() * (10-1 + 1)) + 1,
    reason: '$48',

  },
  {
    id: 6,
    name: 'Earthen Bottle',
    rating: Math.floor(Math.random() * (10-1 + 1)) + 1,
    reason: '$48',

  },
  {
    id: 7,
    name: 'Earthen Bottle',
    rating: Math.floor(Math.random() * (10-1 + 1)) + 1,
    reason: '$48',

  },
  {
    id: 8,
    name: 'Earthen Bottle',
    rating: Math.floor(Math.random() * (10-1 + 1)) + 1,
    reason: '$48',

  },
  {
    id: 9,
    name: 'Earthen Bottle',
    rating: Math.floor(Math.random() * (10-1 + 1)) + 1,
    reason: '$48',

  },
  {
    id: 10,
    name: 'Earthen Bottle',
    rating: Math.floor(Math.random() * (10-1 + 1)) + 1,
    reason: '$48',

  },]
</script>

<template>
  <div class="w-full mt-4">
    <Menu name="Имя"/>
    <div class="flex justify-center mt-10 mb-10 font-black">
      Последние 20 игроков
    </div>
    <PlayersGrid :players="players"/>
  </div>
</template>
