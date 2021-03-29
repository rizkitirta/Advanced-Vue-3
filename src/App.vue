<template lang="">
<div> Ini Adalah Parent Component </div>
<child-component v-for="todo in
  todos" :key="todo" :text="todo" />
</template>

<script>
import childComponent from "./components/childComponent.vue";
export default {
    components: {
        childComponent,
    },
    data() {
        return {
            todos: ["pertama", "kedua", "ketiga"],
        };
    },
};
</script>

<style lang=""></style>
