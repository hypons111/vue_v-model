<template>
  <div class="vModel_1">
    <p>{{ vModel }}</p>
    <input type="text" v-model="vModel">
  </div>
</template>

<script setup>
import { ref } from 'vue'
const vModel = ref("This is v-model_1")

</script>


