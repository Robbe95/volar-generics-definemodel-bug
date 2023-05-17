<script setup lang="ts" generic="t">
defineProps<{ randomProp: string }>();
const model = defineModel<string>();
</script>

<template>
  <div>
    <div>
      {{ randomProp }}
    </div>
    <input style="background-color: red" v-model="model" />
  </div>
</template>

