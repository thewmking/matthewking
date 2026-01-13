<script setup>
import TileCard from '@/components/TileCard.vue'
import avatar from '@/assets/icons/avatar_2.png';
</script>

<template>
  <TileCard title="Bio">
    <template #body>
      <div class="bio-section">
        <div class="bio-photo-wrapper">
          <img class="bio-photo" :src="avatar" />
        </div>
        <p class="bio-text">
          I'm a Raleigh, NC native with a background in digital marketing and a passion for solving puzzles with code. 
          You can find me working all over the stack, from front-end to back-end, as a product owner, manager, or individual contributor.
          I've worked modernizing legacy systems, building new products from scratch, and everything in between.
          I'm a big fan of Vue.js and Rails, but I'm always looking to learn new things and expand my skillset.
          I'm currently building ad tech of the future at Launch Labs.
        </p>
      </div>
    </template>
  </TileCard>
</template>

<style scoped>
.bio-photo-wrapper {
  display: flex;
  justify-content: center;
  margin-bottom: 1rem;
}
.bio-photo {
  background-color: #f0f0f0;
  border-radius: 50%;
  height: 200px;
  margin: 0 auto;
  width: 200px;
}
</style>