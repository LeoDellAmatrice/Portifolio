<script setup>

import HeaderNavList from "@/Header/Header-components/Header-nav-list.vue";
import HeaderNavMobile from "@/Header/Header-components/Header-nav-mobile.vue";
import HeaderLogo from "@/Header/Header-components/Header-logo.vue";
</script>

<template>
  <header>
    <div class="container">
      <HeaderLogo/>
      <nav>
        <HeaderNavList/>
        <HeaderNavMobile/>
      </nav>
    </div>
  </header>
</template>

<style scoped>
header {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  z-index: 1000;
  background-color: var(--white);
  box-shadow: var(--box-shadow);
  transition: var(--transition);
}

header .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 80px;
}
</style>