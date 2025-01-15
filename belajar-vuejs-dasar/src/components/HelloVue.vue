<script setup>
console.log("Hello Vue");

const hello = "<h1>Hello Vue</h1>";
</script>

<template>
  <h1 class="hello">{{ hello }}</h1>
  <div v-html="hello"></div>
</template>

<style scoped>
.hello {
  color: greenyellow;
  background-color: black;
  font-weight: normal;
}
</style>
