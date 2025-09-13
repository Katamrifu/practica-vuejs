<template>
  <div class="card-component secondary">
    <div class="card-icon">
      <span class="icon">🎨</span>
    </div>
    <div class="card-content">
      <h2 class="card-title">Galeria de fotos</h2>
     
      <p class="card-text">
   
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'compnt2',
};
</script>

<style scoped>
.card-component {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  padding: 1.5rem;
  border-radius: 15px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  margin-bottom: 1rem;
  transition: transform 0.3s ease;
  transform: translateX(-20%);
}

.card-component:hover {
  transform: translateY(-5px) translateX(-20%);
}

.secondary {
  background-color: #0596afff;  
  color: #333;
}

.card-icon {
  margin-bottom: 1rem;
}

.icon {
  font-size: 2.5rem;
  color: #fff;
}

.card-title {
  font-size: 1.5rem;
  font-weight: bold;
  margin: 0 0 0.5rem;
}

.card-text {
  font-size: 1rem;
  margin: 0;
}

.card-image {
  width: 100%;
  max-width: 150px;
  border-radius: 10px;
  margin-top: 1rem;
}
</style>
