<script setup>

</script>

<template>
  <ul>
    <li><a href="#home">Início</a></li>
    <li><a href="#sobre">Sobre</a></li>
    <li><a href="#habilidades">Habilidades</a></li>
    <li><a href="#portfolio">Portfólio</a></li>
    <li><a href="#contato">Contato</a></li>
  </ul>
</template>

<style scoped>
ul {
  display: flex;
}

ul li {
  margin-left: 30px;
}

ul li a {
  font-weight: 600;
  position: relative;
  padding: 5px 0;
}

ul li a::after {
  content: '';
  position: absolute;
  bottom: 0;
  left: 0;
  width: 0;
  height: 2px;
  background-color: var(--secondary-color);
  transition: var(--transition);
}

ul li a:hover::after {
  width: 100%;
}

</style>