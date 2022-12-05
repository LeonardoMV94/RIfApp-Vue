<script setup lang="ts">
import NumerosRifa from 'src/components/NumerosRifa.vue';

let numeros: number[] = [];
for (let i = 1; i <= 100; i++) {
  numeros.push(i);
}
</script>
<template>
  <q-page padding class="row justify-center">
    <div padding="none" v-for="num in numeros" :key="num">
      <NumerosRifa :numeroProp="num"></NumerosRifa>
    </div>
  </q-page>
</template>

<style scoped></style>
