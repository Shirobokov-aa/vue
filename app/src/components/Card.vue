<!-- Тег JS вся JS печатается в теге <script> -->
<script setup>
// export default {
//   data() {
//     return {
//       count: 0
//     }
//   },
//   methods: {
//     incriment() {
//       this.count++
//     }
//   }
// }

// Композитный подход
import { ref } from 'vue'
let count = ref(0)
function incriment() {
  count.value++
}
</script>

<!-- Тег HTML весь код печатается в теге HTML <template> -->
<template>
  <div class="card">
    <div class="card__tittle">T-shot BOSS</div>
    <div class="card__price">15.000 rub</div>
  </div>
  <!-- <h2>{{ count }}</h2>
  <button @click="incriment">Добавить 1</button>
  <input v-model="count" /> -->
</template>

<!-- Тег CSS весь код пишется в теге <style> -->
<style scoped>
body {
  background-color: rgb(0, 104, 0);
}
.card__tittle {
  font-size: 100px;
}
</style>
