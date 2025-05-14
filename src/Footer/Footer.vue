<script setup>

</script>

<template>
  <footer>
    <div class="container">
      <div class="footer-content">
        <div class="footer-logo">
          <a href="#"><span>Leonardo Dell'Amatrice</span></a>
        </div>
        <div class="footer-links">
          <ul>
            <li><a href="#home">Início</a></li>
            <li><a href="#sobre">Sobre</a></li>
            <li><a href="#habilidades">Habilidades</a></li>
            <li><a href="#portfolio">Portfólio</a></li>
            <li><a href="#contato">Contato</a></li>
          </ul>
        </div>
        <div class="footer-social">
          <a href="#"><i class="fab fa-github"></i></a>
          <a href="#"><i class="fab fa-linkedin"></i></a>
          <a href="#"><i class="fab fa-behance"></i></a>
          <a href="#"><i class="fab fa-dribbble"></i></a>
        </div>
      </div>
      <div class="footer-bottom">
        <p>&copy; <span id="year"></span> Leonardo Dell'Amatrice Silva. Todos os direitos reservados.</p>
      </div>
    </div>
  </footer>
</template>

<style scoped>
footer {
  background-color: var(--dark-color);
  color: var(--white);
  padding: 50px 0 0;
}

.footer-content {
  display: flex;
  justify-content: space-between;
  margin-bottom: 50px;
}

.footer-logo a {
  font-size: 1.8rem;
  font-weight: 700;
  color: var(--white);
  font-family: var(--font-secondary);
}

.footer-logo span {
  color: var(--secondary-color);
}

.footer-links ul li {
  margin-bottom: 10px;
}

.footer-links ul li a:hover {
  color: var(--secondary-color);
}

.footer-social {
  display: flex;
  gap: 15px;
}

.footer-social a {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  background-color: rgba(255, 255, 255, 0.1);
  color: var(--white);
  transition: var(--transition);
}

.footer-social a:hover {
  background-color: var(--secondary-color);
  transform: translateY(-5px);
}

.footer-bottom {
  text-align: center;
  padding: 20px 0;
  border-top: 1px solid rgba(255, 255, 255, 0.1);
  color: var(--text-light);
  font-size: 0.9rem;
}
</style>