<template lang="">
<div> {{ total }} </div>
    <input v-model="num1" />
    <input v-model="num2" />
</template>
<script>
export default {
    data() {
        return {
            num1:0,
            num2:0
        }
    },
    computed:{
        total(){
            if(this.num1 > this.num2){
                return 'Input Pertama Lebih Besar'      
            }

            return 'Inputan Kedua Lebih Besar'
        }
    }
}
</script>
<style lang="">
    
</style>