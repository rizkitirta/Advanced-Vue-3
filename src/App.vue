<template lang="">
<div> {{ message }} </div>

<input v-model="message"/>

<button @click="addDiscount">+ discount</button>
</template>
<script>
export default {
  data() {
      return {
          message: 'Hello World'
      }
  },
  watch: {
      message(value) {
          console.log('Perubahan di message' + value);
      }
  }
}
</script>
<style lang="">
    
</style>