<template lang="">
	<div>
		Ini Adalah Parent Component
	</div>
	<child-component text="ini component props" />
	<child-component :text="message" />
</template>
<script>
import childComponent from './components/childComponent.vue'
export default {
	components: {
		childComponent
	},
	data() {
		return {
			message:'hello world'
		}
	},
}
</script>
<style lang="">
	
</style>