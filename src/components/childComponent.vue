<template lang="">
<div>Header</div>
<slot/>
<div>Footer</div>
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
                this.$emit("update:modelValue", value);
            },
        },
    },
};
</script>

<style lang=""></style>
