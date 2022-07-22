<template>
	<div>
		<select v-model="selectedCity">
			<option value=""></option>
			<option value="02">서울</option>
			<option value="051">부산</option>
			<option value="054">제주</option>
		</select>
	</div>
</template>
<script>
export default {
	data() {
		return {
			selectedCity: '02'
		}
	},
	setup() {},
	created() {},
	mounted() {},
	unmounted() {},
	methods: {}
}
</script>