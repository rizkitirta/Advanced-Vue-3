<template lang="">
<div id="lifecycle"> {{ message }} </div>
</template>

<script>
import childComponent from "./components/childComponent.vue";
export default {
    data() {
        return {
            message: 'Hello world'
        }
    },
    beforeCreate() {
        console.log('before crated');
        console.log(this.message);
        console.log(document.getELementById('lifecycle'));
    },
    created() {
        console.log('created')
    },
    beforeMount() {
        console.log('before mount')
    },
    mounted() {
        console.log('mounted')
    },
    beforeUpdate() {
        console.log('before update')
    },
    updated() {
        console.log('updated')
    },
    onBeforeUnmount() {
        console.log('before destroy')
    },
    unmounted() {
        console.log('before destroyed')
    },
};
</script>

<style lang=""></style>
