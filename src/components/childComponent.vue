<template lang="">
<div>Title</div>
<slot :data="title"/>
<div>Content</div>
<slot name="slot2" :data="content"/>
<div>Footer</div>
<slot name="slot3" :data="footer"/>
</template>

<script>
export default {
    data() {
        return {
            title: 'Ini Adalah title',
            content: 'Ini Adalah Content',
            footer: 'Ini Adalah Footer'
        }
    },
};
</script>

<style lang=""></style>
