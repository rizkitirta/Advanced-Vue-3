<template lang="">
<div> <span>Ini adalah child component</span> <button @click="onPress">Click
        Dari Child</button> </div>
</template>

<script>
export default {
    emits: ["child-click"],
    methods: {
        onClick() {
            console.log('click saya');
        },
        onPress(value) {
            this.$emit("child-click", "value");
        },
    },
};
</script>

<style lang=""></style>
