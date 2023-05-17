<script setup lang="ts">
import { ref } from "vue";
import ComponentWithGenericAndDefineModel from "./components/ComponentWithGenericAndDefineModel.vue";

const model = ref("");
</script>

<template>
  <div>
    {{ model }}
  </div>
  <ComponentWithGenericAndDefineModel :random-prop="'random stuff'" v-model="model" />
</template>

