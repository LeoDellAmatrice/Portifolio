<script setup>

</script>

<template>
  <section id="contato" class="contact">
    <div class="container">
      <h2 class="section-title">Entre em Contato</h2>
      <div class="contact-content">
        <div class="contact-info">
          <h3>Vamos conversar!</h3>
          <p>Estou disponível para oportunidades de trabalho e projetos freelance. Entre em contato e responderemos o mais breve possível.</p>

          <div class="info-item">
            <i class="fas fa-envelope"></i>
            <p>seuemail@exemplo.com</p>
          </div>
          <div class="info-item">
            <i class="fas fa-phone"></i>
            <p>+55 (XX) XXXX-XXXX</p>
          </div>
          <div class="info-item">
            <i class="fas fa-map-marker-alt"></i>
            <p>Sua Cidade, Estado - País</p>
          </div>

          <div class="social-links">
            <a href="#"><i class="fab fa-github"></i></a>
            <a href="#"><i class="fab fa-linkedin"></i></a>
            <a href="#"><i class="fab fa-behance"></i></a>
            <a href="#"><i class="fab fa-dribbble"></i></a>
          </div>
        </div>
        <div class="contact-form">
          <form>
            <div class="form-group">
              <input type="text" placeholder="Seu Nome" required>
            </div>
            <div class="form-group">
              <input type="email" placeholder="Seu Email" required>
            </div>
            <div class="form-group">
              <input type="text" placeholder="Assunto">
            </div>
            <div class="form-group">
              <textarea placeholder="Sua Mensagem" required></textarea>
            </div>
            <button type="submit" class="btn-primary">Enviar Mensagem</button>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.contact-content {
  display: flex;
  gap: 50px;
  margin-top: 50px;
}

.contact-info {
  flex: 1;
}

.contact-info h3 {
  font-size: 1.8rem;
  margin-bottom: 20px;
  font-family: var(--font-secondary);
  color: var(--dark-color);
}

.contact-info p {
  color: var(--text-light);
  margin-bottom: 30px;
}

.info-item {
  display: flex;
  align-items: center;
  margin-bottom: 20px;
}

.info-item i {
  width: 40px;
  height: 40px;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: var(--light-color);
  color: var(--secondary-color);
  border-radius: 50%;
  margin-right: 15px;
}

.contact-form {
  flex: 1;
}

.form-group {
  margin-bottom: 20px;
}

.form-group input,
.form-group textarea {
  width: 100%;
  padding: 12px 15px;
  border: 1px solid #ddd;
  border-radius: var(--border-radius);
  font-family: var(--font-primary);
  transition: var(--transition);
}

.form-group input:focus,
.form-group textarea:focus {
  outline: none;
  border-color: var(--secondary-color);
}

.form-group textarea {
  min-height: 150px;
  resize: vertical;
}
</style>