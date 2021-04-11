<template>
  <teleport to="#target-teleport">
    <home />
  </teleport>
</template>
<script>
import Home from "./components/Home.vue";
export default {
  components: { Home },
};
</script>
<style></style>
