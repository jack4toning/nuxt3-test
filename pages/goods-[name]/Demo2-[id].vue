<template>
  <!-- <div class="">获得的ID: {{ $route.params.id }}</div> -->
  <div class="">获得的Name: {{ name }}</div>
  <div class="">获得的ID: {{ id }}</div>
</template>

<script setup>
import { ref } from 'vue';

const route = useRoute();
const id = ref(route.params.id);
const name = ref(route.params.name);
</script>

<style scoped></style>
