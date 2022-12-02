<template>
  <AsyncContent />
</template>
<script>
import { defineAsyncComponent } from "vue";
export default {
  components: {
    AsyncContent: defineAsyncComponent(() => import("./AsyncContent.vue")),
  },
};
</script>