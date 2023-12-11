<!-- Тег JS вся JS печатается в теге <script> Атрибут setup обязателен при помощи него подключаем компоненты и подключение реактивных  -->
<script setup>
import Card from './components/Card.vue'
</script>

<!-- Тег HTML весь код печатается в теге HTML <template> -->
<template>
  <div class="card__title">Загаловок</div>
  <svg>
    <use href></use>
  </svg>
  <Card title="рубашка 1" price="300000" />
</template>

<!-- Тег CSS весь код пишется в теге <style> -->
<style>
body {
  background-color: rgb(107, 0, 0);
}
</style>
