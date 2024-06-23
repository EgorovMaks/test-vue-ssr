<template>
  <div id="app">
    <router-view />
    <footer>
      {{ $t("footerText") }}
    </footer>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "App",
});
</script>

<style scoped>
/* ваши стили */
</style>
