<script>import { ref } from 'vue'
import { computed } from 'vue'

const temperature = ref(8)
console.log(temperature.value)
temperature.value = 10
console.log(temperature.value)  
const plusOne = computed(() => temperature.value + 1)

console.log(plusOne.value) 



</script>
<template>
  <div>
    <h2>Convertisseur Temperature</h2>
    <p>{{ temperature }}°F</p>
  </div>
</template>

<style></style>
