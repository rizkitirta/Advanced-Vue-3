<template lang="">
  <div v-for="post in posts" :key="post" > <span> {{ post.name }} </span> </div>
</template>

<script>
export default {
  data() {
    return {
      posts: [],
    };
  },
  async created() {
    // GET request using fetch with async/await
    const response = await fetch("https://jsonplaceholder.typicode.com/users/");
    const data = await response.json();
    this.posts = data;
  },
};
</script>

<style lang=""></style>
