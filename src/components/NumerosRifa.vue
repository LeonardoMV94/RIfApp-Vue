<script setup lang="ts">
interface NumeroRifa {
  numeroProp: number;
}
const props = defineProps<NumeroRifa>();
const bg = 'primary';
</script>

<template>
  <q-btn size="md" :color="bg">
    {{ props.numeroProp }}
  </q-btn>
</template>

<style scoped></style>
