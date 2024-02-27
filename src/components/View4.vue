<template>
  <div class="blog">
    <h1>Blog</h1>
    <div class="blog-post">
      <h2>Las últimas tendencias de moda para el 2022</h2>
      <p>En este artículo, exploramos las últimas tendencias de moda para el 2022. Desde colores vibrantes hasta estampados audaces, este año está lleno de estilos emocionantes...</p>
      <button>Leer más</button>
    </div>
    <!-- Más publicaciones de blog aquí -->
  </div>
</template>

<script>
  export default {
    name: 'ViewFour'
  }
</script>

<style scoped>
.blog {
  padding: 50px 0;
  text-align: center;
}
.blog-post {
  border: 1px solid #ccc;
  padding: 20px;
  margin-bottom: 20px;
  background-color: #f8f9fa;
  border-radius: 10px;
}
</style>