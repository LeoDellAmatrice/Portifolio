<script setup>

</script>

<template>
  <div class="social-links">
    <a href="#"><i class="fab fa-github"></i></a>
    <a href="#"><i class="fab fa-linkedin"></i></a>
    <a href="#"><i class="fab fa-behance"></i></a>
    <a href="#"><i class="fab fa-dribbble"></i></a>
  </div>
</template>

<style scoped>

.social-links {
  display: flex;
  gap: 15px;
  margin: 30px 0;
}

.social-links a {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  background-color: var(--light-color);
  color: var(--dark-color);
  transition: var(--transition);
}

.social-links a:hover {
  background-color: var(--secondary-color);
  color: var(--white);
  transform: translateY(-5px);
}

</style>