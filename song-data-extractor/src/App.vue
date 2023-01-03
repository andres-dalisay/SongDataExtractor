<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <form method="get">
    <label for="spotify-url">URL</label>
    <input type="text" name="spotify-url" id="spotify-url"/>

    <button type="submit">Submit</button>
  </form>
</template>

<style scoped>

</style>
