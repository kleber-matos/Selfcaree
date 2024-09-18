<script setup>
import produtos from "../../produtos.json";
</script>

<template>
  <h2>lista de produtos - teste</h2>

  <div v-for="(produto, index) in produtos" :key="index">
    <h2>{{ produto.nome }}</h2>
  </div>
</template>

<style scoped lang="scss"></style>
