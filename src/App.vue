<script setup>
const mun = ref(2)
function clickMe() {
  num.value++
}
return { num, clickMe }
</script>

<template>
  <div>
    {{ num }}
    <button type="button" @click="clickMe">點我</button>
  </div>
</template>
