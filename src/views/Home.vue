<template>
  <h3>{{ meals[0] }}</h3>
</template>

<script setup>
import { computed } from "vue";
import store from "../store";


const meals = computed(() => store.state.meals)

</script>