<template lang="">
<child>
<span>Sisipan</span>
</child>
</template> 

<script>
import Child from "./components/childComponent.vue";
export default {
  components: {
    Child
  },
  data() {
    return {
      message: ""
    }
  }
};
</script>
