<template>
  <main class="columns is-gapless is-multine">
    <div class="column is-one-quarter">
      <SideBar />
    </div>
    <div class="column is-three-quarter">
      <FormContent />
    </div>
  </main>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import SideBar from "./components/SideBar.vue";
import FormContent from "./components/FormContent.vue";

export default defineComponent({
  name: "App",
  components: {
    SideBar,
    FormContent
  },
});
</script>

<style>
</style>
