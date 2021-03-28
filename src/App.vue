<template lang="">
  <div>
    {{message}}
  </div>
  <span :title='message'>blalala</span>
</template>
<script>
export default {
  data() {
    return {
      message: 'Hello World'
    }
  },
}
</script>
<style lang="">
  
</style>