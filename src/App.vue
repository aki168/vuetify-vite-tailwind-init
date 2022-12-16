<template>
  <v-app>
    <v-main>
      <!-- <HelloWorld /> -->
      <v-alert color="info" icon="$info">
        I'm an info alert that uses <strong>color</strong> and <strong>icon</strong> props instead of
        <strong>type</strong>
      </v-alert>
    </v-main>
  </v-app>
</template>

<script setup>
import HelloWorld from '@/components/HelloWorld.vue'
</script>
