<script setup lang="ts">
interface Props {
  name: string;
}
const props = defineProps<Props>();
</script>
<template>
  <span>hello: {{ props.name }}</span>
</template>
<style scoped></style>
