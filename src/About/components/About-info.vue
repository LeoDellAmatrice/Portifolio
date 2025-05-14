<script setup>

</script>

<template>
  <div class="about-info">
    <div class="info-item">
      <span>Nome:</span>
      <p>Leonardo Dell'Amatrice Silva</p>
    </div>
    <div class="info-item">
      <span>Email:</span>
      <p>Leonardo.dellamatrice@gmail.com</p>
    </div>
    <div class="info-item">
      <span>Idade:</span>
      <p>17 anos</p>
    </div>
    <div class="info-item">
      <span>De:</span>
      <p>Brasil</p>
    </div>
  </div>
</template>

<style scoped>

.about-info {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 20px;
  margin-bottom: 30px;
}

.info-item span {
  font-weight: 600;
  color: var(--dark-color);
}

.info-item p {
  color: var(--text-light);
}
</style>