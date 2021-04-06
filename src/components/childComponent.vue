<template lang="">
<div>Header</div>
<slot />
<div>Content</div>
<slot name="slot2"/>
<div>Footer</div>
<slot name="slot3"/>
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
