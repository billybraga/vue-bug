<script setup>
import { ref } from 'vue'
import parent from './Parent.vue'

const parentModel = ref("")
</script>

<template>
  <parent v-model="parentModel" />
  <br />
  parentModel: {{ parentModel }}
</template>