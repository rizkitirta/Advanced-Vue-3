<template lang="">
<div :class="status ? 'success' : 'failed'"> Status </div>
<button @click="status = !status">Change !</button>
<div :class="[boldClass,greenClass]">Test</div>
</template>
<script>
export default {
  data() {
      return {
          status: true,
          boldClass: 'bold',
          greenClass: 'success'
      }
  },
}
</script>
<style>
.success {
    color: green;
}
.failed {
    color: red;
}
.bold {
    font-weight: bold;
}
</style>