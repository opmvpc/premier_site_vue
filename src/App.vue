<script setup>
import Footer from "./components/Footer.vue";
import Nav from "./components/Nav.vue"
import PrimaryButton from "./components/PrimaryButton.vue";
const year = new Date().getFullYear()
</script>

<template>
  <Nav></Nav>
  <main class="p-8">

  </main>
  <h1 class="text-3xl font-bold underline text-red-500">
    Hello world!
  </h1>
  <PrimaryButton>Click !</PrimaryButton>
  <Footer>
    © Thibault Six - {{ year }}
  </Footer>
</template>
