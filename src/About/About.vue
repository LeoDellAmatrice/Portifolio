<script setup>

import AboutText from "@/About/components/About-text.vue";
import AboutImage from "@/About/components/about-image.vue";
</script>

<template>
  <section id="sobre" class="about">

    <div class="container">

      <h2 class="section-title">Sobre Mim</h2>

      <div class="about-content">

        <about-image/>

        <about-text/>

      </div>

    </div>

  </section>
</template>

<style scoped>
.about .container {
  display: flex;
  flex-direction: column;
}

.about-content {
  display: flex;
  gap: 0;
  align-items: center;
}
</style>