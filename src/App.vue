<template lang="">
<child ref="childComponent" @child-click="onPress" />

<button @click="clickSaya">Clik Dari Parent</button> 
</template>

<script>
import Child from "./components/childComponent.vue";
export default {
  components: {
    Child,
  },
  methods: {
    onPress(val) {
      console.log(val);
    },
    clickSaya() {
        this.$refs.childComponent.onClick();
    }
  },
};
</script>
