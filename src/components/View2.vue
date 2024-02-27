
<template>
 <div class="services">
    <h1>Nuestros Servicios</h1>
    <div class="service-card">
      <h2>Personal Shopper</h2>
      <p>¿No estás seguro de qué estilo te queda mejor? Nuestros personal shoppers están aquí para ayudarte a encontrar el look perfecto.</p>
    </div>
    <div class="service-card">
      <h2>Entrega rápida</h2>
      <p>Ofrecemos envío rápido y confiable para que puedas disfrutar de tus nuevas prendas lo antes posible.</p>
    </div>
    <div class="service-card">
      <h2>Devoluciones fáciles</h2>
      <p>Si no estás completamente satisfecho con tu compra, facilitamos las devoluciones y los cambios.</p>
    </div>
  </div>
</template>
  
  <script>
  export default {
    name: 'ViewTwo'
  }
  </script>



<style scoped>
.services {
  padding: 50px 0;
  text-align: center;
}
  .service-card {
  border: 1px solid #ccc;
  padding: 20px;
  margin-bottom: 20px;
  background-color: #f8f9fa;
  border-radius: 10px;
}
</style>