<template lang="">
<div>{{ message }}</div>

<div> {{ number }} </div>
</template>

<script>
export default {
    props: {
        message: String,
        number: {
            type: Number,
            default: 0
        }
    }
};
</script>

<style lang=""></style>
