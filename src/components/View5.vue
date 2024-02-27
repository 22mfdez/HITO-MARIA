<template>
    <div class="faq">
      <h1>Preguntas Frecuentes</h1>
      <div class="faq-item">
        <h2>¿Cómo puedo rastrear mi pedido?</h2>
        <p>Después de realizar un pedido, recibirás un correo electrónico con un número de seguimiento. Puedes usar este número para rastrear tu pedido en la página de seguimiento de nuestro sitio web.</p>
      </div>
      <div class="faq-item">
        <h2>¿Qué métodos de pago aceptan?</h2>
        <p>Aceptamos todas las principales tarjetas de crédito, así como PayPal y Apple Pay. Lamentablemente, no podemos aceptar cheques ni pagos en efectivo.</p>
      </div>
      <div class="faq-item">
        <h2>¿Puedo devolver o cambiar un artículo?</h2>
        <p>Sí, ofrecemos devoluciones y cambios dentro de los 30 días posteriores a la compra. Para más detalles, por favor consulta nuestra política de devoluciones.</p>
      </div>
      <!-- Más preguntas y respuestas aquí -->
    </div>
  </template>
  
  <script>
    export default {
      name: 'ViewFive'
    }
  </script>
  
  <style scoped>
  .faq {
    padding: 50px 0;
    text-align: center;
  }
  .faq-item {
    border: 1px solid #ccc;
    padding: 20px;
    margin-bottom: 20px;
    background-color: #f8f9fa;
    border-radius: 10px;
  }
  </style>