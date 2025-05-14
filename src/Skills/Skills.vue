<script setup>

</script>

<template>
  <section id="habilidades" class="skills">
    <div class="container">
      <h2 class="section-title">Minhas Habilidades</h2>
      <div class="skills-content">
        <div class="skills-description">
          <h3>Minhas Habilidades e Experiências</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
        </div>
        <div class="skills-progress">
          <div class="skill-item">
            <div class="skill-info">
              <span>HTML/CSS</span>
              <span>95%</span>
            </div>
            <div class="progress-bar">
              <div class="progress" style="width: 95%;"></div>
            </div>
          </div>
          <div class="skill-item">
            <div class="skill-info">
              <span>JavaScript</span>
              <span>85%</span>
            </div>
            <div class="progress-bar">
              <div class="progress" style="width: 85%;"></div>
            </div>
          </div>
          <div class="skill-item">
            <div class="skill-info">
              <span>UI/UX Design</span>
              <span>80%</span>
            </div>
            <div class="progress-bar">
              <div class="progress" style="width: 80%;"></div>
            </div>
          </div>
          <div class="skill-item">
            <div class="skill-info">
              <span>React</span>
              <span>75%</span>
            </div>
            <div class="progress-bar">
              <div class="progress" style="width: 75%;"></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.skills-content {
  display: flex;
  gap: 50px;
  margin-top: 50px;
}

.skills-description {
  flex: 1;
}

.skills-description h3 {
  font-size: 1.8rem;
  margin-bottom: 20px;
  font-family: var(--font-secondary);
  color: var(--dark-color);
}

.skills-description p {
  color: var(--text-light);
  margin-bottom: 30px;
}

.skills-progress {
  flex: 1;
}

.skill-item {
  margin-bottom: 25px;
}

.skill-info {
  display: flex;
  justify-content: space-between;
  margin-bottom: 10px;
}

.skill-info span {
  font-weight: 600;
  color: var(--dark-color);
}

.progress-bar {
  height: 10px;
  background-color: var(--light-color);
  border-radius: 5px;
  overflow: hidden;
}

.progress {
  height: 100%;
  background-color: var(--secondary-color);
  border-radius: 5px;
  transition: width 1s ease;
}
</style>