<template lang="">
<div>Ini Adalah Component Tiga</div>
<div>{{ providedAuthor }}</div>
</template>

<script>
export default {
   inject: ['providedAuthor']
};
</script>

<style lang=""></style>
