<template lang="">
  <div v-if="status">
  Ini Tampil 
  </div>
  <div v-if="status">Ini True</div>
  <div v-else-if="status">Ini False</div>
  <div v-else>False</div>

  <button @click="setStatus">Button</button>
</template>
<script>
export default {
  data() {
    return {
      status: false
    }
  },
  methods: {
    setStatus(){
      this.status = !this.status
    }
  },
}
</script>
<style lang="">
  
</style>