<template>
    <div class="mb-4">
      <h5>Count: {{ counter.count }}</h5>
      <button class="btn btn-primary" @click="counter.increment">Increment</button>
    </div>
  </template>
  
  <script setup>
  import { useCounterStore } from '../store/counter'
  const counter = useCounterStore()
  </script>
  