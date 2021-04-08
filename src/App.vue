<template lang="">
<satu/>
</template>

<script>
import Satu from "./components/ComponentSatu.vue";
export default {
    components: {Satu},
    data() {
        return {
            author: 'Rizki Tirta'
        }
    },
    provide(){
        return {
            providedAuthor : this.author
        }
    }
};
</script>
