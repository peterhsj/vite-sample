<script setup>
// setup不用 return
import { ref } from 'vue'
const num = ref(2)
function clickMe() {
  num.value++
}
</script>

<template>
  <div>
    {{ num }}
    <button type="button" @click="clickMe">點我</button>
  </div>
</template>
