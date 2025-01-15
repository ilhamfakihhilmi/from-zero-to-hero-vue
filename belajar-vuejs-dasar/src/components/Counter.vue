<script setup>
import { ref } from "vue";

let count = ref(0); //menggunakan let karena nanti nilai dapat berubah

function increment() {
  count.value++;
//   document.getElementById("count").innerText = `Counter : ${count}`;
}
</script>
<template>
  <h1 id="count">Counter: {{ count }}</h1>
  <button v-on:click="increment">increment</button>
</template>
<style scoped></style>
