<template>
    <div>
      <div v-for="(votes, option) in pollOptions" :key="option">
        <button @click="addVote(option)">{{ option }}</button>
        <span> {{ votes }} votos</span>
      </div>
    </div>
  </template>
  
  <script setup>
  import { reactive } from 'vue';
  
  const pollOptions = reactive({
    JavaScript: 0,
    Python: 0,
    Ruby: 0,
    Rust: 0,
  });
  
//TODO.........
  </script>
  