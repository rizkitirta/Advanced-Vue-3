<template lang="">
<div> Ini Adalah Child Component </div>
<div> {{ text }} </div>
</template>

<script>
export default {
    props: {
        text: {
            type: String,
            default: "",
        },
    },
};
</script>

<style lang=""></style>
