<template>
  <div class="not-found">
    <h1>404</h1>
    <h2>Página no encontrada</h2>
    <p>Lo sentimos, la página que buscas no existe o ha sido movida.</p>
    <router-link to="/" class="home-link">
      <button>Volver a la página principal</button>
    </router-link>
  </div>
</template>

<script>
  export default {
    name: 'NotFoundView'
  };
</script>

<style scoped>
  .not-found {
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background: linear-gradient(135deg, #e74c3c, #c0392b);
    color: #ecf0f1;
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
  }

  h1 {
    font-size: 6rem;
    margin: 0;
  }

  h2 {
    font-size: 2rem;
    margin-bottom: 20px;
  }

  p {
    font-size: 1.2rem;
    margin-bottom: 30px;
  }

  /* Estilo para el botón de volver */
  button {
    background-color: #1abc9c;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    color: #fff;
    font-weight: bold;
    cursor: pointer;
    transition: background-color 0.3s ease;
  }

  button:hover {
    background-color: #16a085;
  }

  /* Ajuste para el enlace */
  .home-link {
    text-decoration: none;
  }
</style>