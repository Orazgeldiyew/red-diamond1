<template>
  <header class="header">
    <h1>Red Diamond</h1>
    <nav>
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/donate">Donate Blood</RouterLink>
    </nav>
  </header>
</template>

<script setup lang="ts"></script>

<style scoped>
.header {
  background-color: #b30000;
  padding: 1rem;
  color: white;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
nav a {
  color: white;
  margin-left: 1rem;
  text-decoration: none;
  font-weight: bold;
}
nav a:hover {
  text-decoration: underline;
}
</style>
