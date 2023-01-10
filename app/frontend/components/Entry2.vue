<template>
  <SharedComponent class="parent"/>
</template>


<script setup>
import SharedComponent from "../shared_components/SharedComponent.vue";
</script>

<style scoped>
.parent {
  background-color: red;
  padding: 3rem;
  color: white;
  font-size: 2rem;
}
</style>