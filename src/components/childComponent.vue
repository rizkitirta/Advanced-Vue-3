<template lang="">
<input v-model="value" />
</template>

<script>
export default {
   props: ["modelValue"],
   computed: {
       value: {
           get() {
               return this.modelValue;
           },
           set(value) {
               this.$emit('update:modelValue', value);
           }
       }
   }
};
</script>

<style lang=""></style>
