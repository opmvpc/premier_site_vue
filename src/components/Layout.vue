<script setup>
import Footer from "./Footer.vue";
import Nav from "./Nav.vue"
import PrimaryButton from "./PrimaryButton.vue";

const year = new Date().getFullYear()
</script>

<template>
  <div class="min-h-screen bg-blue-100 flex flex-col">
    <Nav></Nav>

    <main class="p-8 flex-grow">
      <h1 class="text-3xl font-bold underline text-red-500">
        Hello world!
      </h1>
      <PrimaryButton>Click !</PrimaryButton>
  
    </main>

    <Footer>
      © Thibault Six - {{ year }}
    </Footer>

  </div>
</template>
