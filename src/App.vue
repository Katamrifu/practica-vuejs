<template>
  <div id="app">
    <div class="app-container">
      <h1 class="app-title">¡BIENVENIDOS a mi aplicación Vue.js!</h1>
      <p class="app-subtitle">Componentes</p>
      
      <Compnt1 />
      <Compnt2 />
      
      <div class="footer-text">
        <p>Aplicación desarrollada con Vue.js</p>
      </div>
    </div>
  </div>
</template>

<script>
import Compnt1 from './compnt1.vue';
import Compnt2 from './compnt2.vue';

export default {
  name: 'App',
  components: {
    Compnt1,
    Compnt2,
  },
};
</script>

<style>
/* Estilos globales para la aplicación */
body {
  margin: 0;
  padding: 0;
  background-color: #ede7f6; /* Fondo lila claro */
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
}

.app-container {
  width: 90%;
  max-width: 500px;
  background-color: #0fd3c3ff; /* Púrpura de fondo */
  padding: 2rem;
  border-radius: 20px;
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);
}

.app-title {
  font-size: 2rem;
  font-weight: bold;
  color: #fff;
  margin: 0 0 0.5rem;
}

.app-subtitle {
  font-size: 1rem;
  color: #fff;
  margin: 0 0 2rem;
}

.footer-text {
  margin-top: 1.5rem;
  color: #fff;
}
</style>
