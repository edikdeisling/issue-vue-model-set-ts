<script setup lang="ts">
  import { ref } from 'vue';

  const model = ref(new Set());
</script>

<template>
  <label>
    <input type="checkbox" value="1" v-model="model">
    <span>Checkbox 1</span>
  </label>
  <label>
    <input type="checkbox" value="2" v-model="model">
    <span>Checkbox 2</span>
  </label>
  <div>
    <br>
    Current value: {{ model }}
  </div>
</template>

<style></style>
