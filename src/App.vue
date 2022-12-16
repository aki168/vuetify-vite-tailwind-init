<template>
  <v-app>
    <v-main>
      <!-- <HelloWorld /> -->
      <h1 class="text-4xl text-blue-300 py-10 px-2">Tailwind CSS test</h1>
      <v-alert color="success" icon="$info">
        I'm an info alert that uses <strong>color</strong> and <strong>icon</strong> props instead of
        <strong>type</strong>
      </v-alert>
    </v-main>
  </v-app>
</template>

<script setup>
import HelloWorld from '@/components/HelloWorld.vue'
</script>
