<script setup>

import HeroButtons from "@/Section-hero/Hero-components/hero-buttons.vue";
</script>

<template>
  <h1>Olá, eu sou <span>Leonardo Dell'Amatrice Silva</span></h1>
  <h2>Futuro Desenvolvedor de Sistemas</h2>
  <p>Criando soluções digitais com design minimalista e funcional</p>
  <div class="hero-buttons">
    <HeroButtons/>
  </div>
</template>

<style scoped>
h1 {
  font-size: 2.8rem;
  font-weight: 700;
  margin-bottom: 20px;
  line-height: 1.2;
}

h1 span {
  color: var(--secondary-color);
}

h2 {
  font-size: 1.5rem;
  font-weight: 400;
  color: var(--text-light);
  margin-bottom: 20px;
}

p {
  font-size: 1.1rem;
  margin-bottom: 30px;
  color: var(--text-light);
}

.hero-buttons {
  display: flex;
  gap: 20px;
}
</style>