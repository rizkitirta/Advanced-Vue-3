<template lang="">
  <div>
    {{count}}
  </div>
  <button @click="count++">Add</button>
  <button @click="addCount">Add count</button>
</template>
<script>
export default {
  data() {
    return {
      count: 0
    }
  },
  methods: {
    addCount(){
      this.count+=2;
    }
  },
}
</script>
<style lang="">
  
</style>