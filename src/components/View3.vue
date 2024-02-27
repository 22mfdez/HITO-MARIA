<template>
  <div class="contact">
    <h1>Contacto</h1>
    <form>
      <input type="text" placeholder="Tu nombre" />
      <input type="email" placeholder="Tu email" />
      <textarea placeholder="Tu mensaje"></textarea>
      <div class="button-container">
        <button type="submit">Enviar</button>
      </div>
    </form>
  </div>
</template>

<script>
  export default {
    name: 'ViewThree'
  }
</script>

<style scoped>
.contact {
  padding: 50px 0;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.contact form {
  display: flex;
  flex-direction: column;
  width: 100%;
  max-width: 600px;
}
.contact form input,
.contact form textarea {
  margin-bottom: 20px;
  padding: 10px;
  width: 100%;
}
.button-container {
  text-align: center;
}
</style>