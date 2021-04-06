<template lang="">
<child>
    <template v-slot:default>
        <span>Ini Adalah Judul</span>
    </template>

    <template v-slot:slot2>
        <span>Ini Adalah Content</span>
    </template>

    <template v-slot:slot3>
        <span>Ini Adalah Footer</span>
    </template>
</child>
</template>

<script>
import Child from "./components/childComponent.vue";
export default {
    components: {
        Child
    },
    data() {
        return {
            message: ""
        }
    }
};
</script>
