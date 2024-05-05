<!-- Use stores to store the counter variable and define two function to add and subcreact from it when pressing on the buttons-->
<script setup>
import { useCounterStore } from "../stores/counterStore";


</script>

<template>
  <div>
    <h1>Counter: {{ counter }}</h1>
    <button>Increment</button>
    <button>Decrement</button>
  </div>
</template>
<style scoped>
button {
  margin: 5px;
  padding: 5px 10px;
  font-size: 16px;
}
</style>
