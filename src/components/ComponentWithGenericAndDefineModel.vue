<script setup lang="ts" generic="T = string">
defineProps<{ randomProp: string }>();
const model = defineModel<T>();
</script>

<template>
  <div>
    <div>
      {{ randomProp }}
    </div>
    <input style="background-color: red" v-model="model" />

  </div>
</template>

