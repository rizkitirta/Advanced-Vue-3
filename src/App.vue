<template lang="">
<child>
    <template v-slot:default="{ data }">
        <span>Judul : {{data}}</span>
    </template>

    <template v-slot:slot2="{data}">
        <span>Konten : {{ data }}</span>
    </template>

    <template v-slot:slot3="{data}">
        <span>Footer : {{data}}</span>
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
