<script setup lang="ts">
import PlayerCard from '../Cards/PlayerCard.vue';

defineProps({
  players: Object
})
</script>

<template>
  <div class="flex justify-center mt-4">
    <div class="grid-cols-5 grid gap-4 w-3/5">
      <PlayerCard v-for="player in players" :key="player.id" :name=player.name :reason=player.reason :rating=player.rating />
    </div>
  </div>
</template>