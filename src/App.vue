<template lang="">
  <div>
    {{message}}
  </div>

<input v-model="message"/>
<input :value="message" @input="message = $event.target.value"/>
</template>
<script>
export default {
  data() {
    return {
      message: 'hallo'
    }
  },
}
</script>
<style lang="">
  
</style>