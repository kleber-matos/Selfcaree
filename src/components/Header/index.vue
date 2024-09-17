<script setup></script>

<template>
  <header>
    <img class="logo" src="../../assets/logo.svg" alt="Logo" />

    <figure>
      <img src="../../assets/lupa.png" alt="Lupa" />
      <img src="../../assets/usuario.png" alt="Usuario" />
      <img src="../../assets/carrinho.png" alt="Carrinho" />
    </figure>
  </header>
</template>

<style scoped>
header {
  border: solid;
  display: flex;
  justify-content: space-between;
}

img {
  cursor: pointer;
}

.logo {
  margin-left: 15px;
}

figure {
  width: 15vw;
  display: flex;
  max-width: 200px;
  justify-content: space-evenly;
}
</style>
