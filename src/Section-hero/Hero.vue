<script setup>

import HeroContent from "@/Section-hero/Hero-components/hero-content.vue";
</script>

<template>
  <section id="home" class="hero">
    <div class="container">
      <div class="hero-content">
        <hero-content/>
      </div>
      <div class="hero-image">
        <img src="https://placehold.co/400x400" alt="Leonardo Dell'Amatrice">
      </div>
    </div>
  </section>
</template>

<style scoped>
.hero {
  height: 100vh;
  display: flex;
  align-items: center;
  background-color: var(--light-color);
  padding-top: 80px;
}

.hero .container {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.hero-content {
  flex: 1;
  padding-right: 50px;
}

.hero-image {
  flex: 1;
  text-align: center;
}

.hero-image img {
  border-radius: var(--border-radius);
  box-shadow: var(--box-shadow);
  max-width: 400px;
}
</style>