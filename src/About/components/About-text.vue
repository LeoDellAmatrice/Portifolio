<script setup>

import AboutInfo from "@/About/components/About-info.vue";
import AboutLinks from "@/About/components/About-links.vue";
</script>

<template>
  <div class="about-text">
    <h3>Quem sou eu?</h3>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>

    <AboutInfo/>

    <AboutLinks/>

    <a href="#" class="btn-primary">Download CV</a>
  </div>
</template>

<style scoped>
.about-text {
  flex: 1;
}

.about-text h3 {
  font-size: 2rem;
  margin-bottom: 20px;
  font-family: var(--font-secondary);
  color: var(--dark-color);
}

.about-text p {
  margin-bottom: 30px;
  color: var(--text-light);
}
</style>