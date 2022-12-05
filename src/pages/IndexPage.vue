<script setup lang="ts"></script>
<template>
  <div>
    <q-page class="row items-center justify-evenly">
      <!-- place QPageScroller at end of page -->
      <q-page-scroller
        position="bottom-right"
        :scroll-offset="150"
        :offset="[18, 18]"
      >
        <q-btn fab icon="keyboard_arrow_up" color="accent" />
      </q-page-scroller>
    </q-page>
  </div>
</template>
