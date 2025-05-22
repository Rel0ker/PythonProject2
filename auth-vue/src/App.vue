<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header
    style="
      width: 100%;
      position: fixed;
      top: 0px;
      left: 0;
      background-color: black;
      padding: 10px;
      text-align: center;
    "
  >
    <a href="/cart" style="margin-right: 20px">Cart</a>
    <a href="/products" style="margin-right: 20px">Products</a>
    <a href="/login" style="margin-right: 20px">Login</a>
  </header>
  <RouterView style="margin-top: 30px" />
</template>
