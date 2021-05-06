<template>
  <div class="login-container">
    <h1 class="title">Pedidos!</h1>
    <div class="data-section">
      <label>Usuario</label>
      <input />
      <label>Contraseña</label>
      <input />
    </div>
    <NuxtLink class="login-btn" to="/landing">Login</NuxtLink>
  </div>
</template>

<style lang="scss" scoped>
.login-container {
  height: 100vh;
  justify-content: center;
  align-items: center;
  display: flex;
  background-color: $primary-color;
  flex-direction: column;

  label {
    margin-top: 1.1rem;
    font-size: 1.4em;
    color: white;
    margin-bottom: 0.6rem;
  }

  input {
    height: 3.3rem;
    min-width: 24rem;
    border-radius: 2.1rem;
  }

  .data-section {
    display: flex;
    flex-direction: column;
  }

  .title {
    color: white;
    font-size: 3.4em;
    margin-bottom: 1rem;
  }

  .login-btn {
    margin-top: 3.7rem;
    text-decoration: none;
    background-color: white;
    color: $primary-color;
    font-size: 1.8em;
    width: 24rem;
    padding: 0.4rem 1rem;
    text-align: center;
    font-weight: 400;
    border-radius: 3rem;
  }
}
</style>
