<template lang="">
<div>{{message}}</div>
<br>
<child v-model="message"/>
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
