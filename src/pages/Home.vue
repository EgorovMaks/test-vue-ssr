<template>
  <div>
    <h1>{{ $t("welcome") }}</h1>
    <router-link to="/about">{{ $t("aboutUs") }}</router-link>
    <router-link to="/services">{{ $t("services") }}</router-link>
    <router-link to="/contact">{{ $t("contact") }}</router-link>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "HomePage",
});
</script>

<style scoped>
/* ваши стили */
</style>
