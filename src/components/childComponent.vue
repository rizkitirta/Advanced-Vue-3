<template lang="">
<input :value="modelValue" @input="$emit('update:modelValue', $event.target.value)"/>
</template>

<script>
export default {
   props: ["modelValue"]
};
</script>

<style lang=""></style>
