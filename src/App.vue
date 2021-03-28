<template lang="">
    <ol>
    <li v-for="(todo, index) in todos" :key="todo.id">
      {{index}} - {{todo.activity}}
    </li>
    </ol>
</template>
<script>
export default {
  data() {
    return {
      todos:[
        {id:1, activity:"Ngoding"},
      {id:2, activity:"Bermain"},
      {id:3, activity:"Memasak"}
      ]
    }
  },
}
</script>
<style lang="">
  
</style>