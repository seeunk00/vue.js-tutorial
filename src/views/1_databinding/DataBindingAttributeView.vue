<template>
	<div>
		<input type="text" name="" id="" v-bind:value="userId" readonly />
		<input type="text" name="" id="" :value="userId" readonly />
		<br>
		<img :src="imgSrc" style="width: 100px; height: auto;" />
		<br>
		<input type="search" name="" id="" v-model="txt1" />
		<button :disabled="txt1 === ''">조회</button>
	</div>
</template>
<script>
export default {
	components: {},
	data() {
		return {
			userId: 'JeonJunWoo',
			imgSrc: 'http://t1.daumcdn.net/media/img-section/sports13/logo/team/1/LT_300300.png',
			txt1: ''
		}
	},
	setup() {},
	created() {},
	mounted() {},
	unmounted() {},
	methods() {},
}
</script>