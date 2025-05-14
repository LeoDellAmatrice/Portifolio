<script setup>

</script>

<template>
  <section id="portfolio" class="portfolio">
    <div class="container">
      <h2 class="section-title">Meu Portfólio</h2>
      <div class="portfolio-filter">
        <button class="active" data-filter="*">Todos</button>
        <button data-filter=".web">Web Design</button>
        <button data-filter=".app">Aplicativos</button>
        <button data-filter=".graphic">Design Gráfico</button>
      </div>
      <div class="portfolio-grid">
        <div class="portfolio-item web">
          <img src="https://placehold.co/400x300/orange/white" alt="Projeto 1">
          <div class="portfolio-overlay">
            <h3>Projeto Web 1</h3>
            <p>Web Design</p>
            <a href="#"><i class="fas fa-link"></i></a>
          </div>
          <div class="portfolio-info">
            <h3>Projeto Web 1</h3>
            <p>Web Design</p>
            <p class="description">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam.</p>
          </div>
        </div>
        <div class="portfolio-item app">
          <img src="https://placehold.co/400x300" alt="Projeto 2">
          <div class="portfolio-overlay">
            <h3>Aplicativo Mobile</h3>
            <p>Desenvolvimento</p>
            <a href="#"><i class="fas fa-link"></i></a>
          </div>
          <div class="portfolio-info">
            <h3>Aplicativo Mobile</h3>
            <p>Desenvolvimento</p>
            <p class="description">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam.</p>
          </div>
        </div>
        <div class="portfolio-item graphic">
          <img src="https://placehold.co/400x300" alt="Projeto 3">
          <div class="portfolio-overlay">
            <h3>Identidade Visual</h3>
            <p>Design Gráfico</p>
            <a href="#"><i class="fas fa-link"></i></a>
          </div>
        </div>
        <div class="portfolio-item web">
          <img src="https://placehold.co/400x300" alt="Projeto 4">
          <div class="portfolio-overlay">
            <h3>Projeto Web 2</h3>
            <p>Web Design</p>
            <a href="#"><i class="fas fa-link"></i></a>
          </div>
        </div>
        <div class="portfolio-item app">
          <img src="https://placehold.co/400x300" alt="Projeto 5">
          <div class="portfolio-overlay">
            <h3>App Dashboard</h3>
            <p>Desenvolvimento</p>
            <a href="#"><i class="fas fa-link"></i></a>
          </div>
        </div>
        <div class="portfolio-item graphic">
          <img src="https://placehold.co/400x300" alt="Projeto 6">
          <div class="portfolio-overlay">
            <h3>Branding</h3>
            <p>Design Gráfico</p>
            <a href="#"><i class="fas fa-link"></i></a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.portfolio-filter {
  display: flex;
  justify-content: center;
  gap: 15px;
  margin-bottom: 50px;
}

.portfolio-filter button {
  padding: 8px 20px;
  background-color: transparent;
  border: 1px solid var(--secondary-color);
  color: var(--secondary-color);
  border-radius: 30px;
  cursor: pointer;
  transition: var(--transition);
  font-weight: 600;
}

.portfolio-filter button.active,
.portfolio-filter button:hover {
  background-color: var(--secondary-color);
  color: var(--white);
}

.portfolio-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
  gap: 30px;
}

.portfolio-item {
  position: relative;
  border-radius: var(--border-radius);
  overflow: hidden;
  box-shadow: var(--box-shadow);
}

.portfolio-item img {
  width: 100%;
  height: 250px;
  object-fit: cover;
  transition: var(--transition);
}

.portfolio-overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(52, 152, 219, 0.9);
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  opacity: 0;
  transition: var(--transition);
  color: var(--white);
  text-align: center;
  padding: 20px;
}

.portfolio-overlay h3 {
  font-size: 1.5rem;
  margin-bottom: 10px;
  transform: translateY(20px);
  transition: var(--transition);
}

.portfolio-overlay p {
  margin-bottom: 20px;
  transform: translateY(20px);
  transition: var(--transition);
  transition-delay: 0.1s;
}

.portfolio-overlay a {
  color: var(--white);
  font-size: 1.5rem;
  transform: translateY(20px);
  transition: var(--transition);
  transition-delay: 0.2s;
}

.portfolio-item:hover .portfolio-overlay {
  opacity: 1;
}

.portfolio-item:hover .portfolio-overlay h3,
.portfolio-item:hover .portfolio-overlay p,
.portfolio-item:hover .portfolio-overlay a {
  transform: translateY(0);
}

.portfolio-item:hover img {
  transform: scale(1.1);
}

.portfolio-info {
  padding: 5px 10px;
}

.portfolio-info .description {
  padding: 5px 0 0 0;
}
</style>