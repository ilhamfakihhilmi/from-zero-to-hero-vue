<script setup>
console.log("Hello Vue");

const hello = "<h1> Hello Vue </h1>";
const classHello = "hello";
const id = "hello";
</script>

<template>
  <h1 :id :class="classHello">{{ hello }}</h1>
  <div :class="classHello" v-html="hello"></div>
</template>

<style scoped>
.hello {
  color: green;
  background-color: beige;
}
</style>