<template>
    <pre>
       {{ $data }}
    </pre>
    <button @click="onPress">Click</button>
</template>
<script>
import basicMixins from './mixins/basic.js';
import mergeMixins from './mixins/merge.js';
export default {
    mixins: [basicMixins,mergeMixins],
    data() {
        return {
            isLoading: false
        }
    },
}
</script>
<style>
    
</style>