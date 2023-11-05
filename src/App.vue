<template>
  <div class="main-content">
    <router-view />
  </div>
</template>

<script lang="ts">
import { defineComponent, watchEffect } from "vue";
import stateStore from "./utils/store";

export default defineComponent({
  name: "App",
  components: {},
  mounted() {
    document.body.classList.add("bg-body-secondary");
  },
  setup() {
    return {};
  },
});
</script>