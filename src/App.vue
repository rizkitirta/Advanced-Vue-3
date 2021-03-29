<template lang="">
    <div v-once>
        {{ message }}
    </div>

    <button @click="message = 'Hello world'">update</button>
</template>
<script>
export default {
    data() {
        return {
            message: 'Hi bro!'
        }
    },
}
</script>
<style lang="">
    
</style>