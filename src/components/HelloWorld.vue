
<template>
  <div class="home">
    <div class="header">
      <h1>Bienvenido a Nuestra Web</h1>
      <p>Ofrecemos los mejores servicios.</p>
      <button>Contacta con nosotros</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

.home{
  margin-top: 100px;
  text-align: center;
  font-size: 20px;
  color: #646ac4fb;
}
</style>
