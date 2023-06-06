<template>
	<div class="card">
		<Banner />
		<BottomBanner />
	</div>
</template>
<script setup>
	import { Banner, BottomBanner } from './index';
</script>
<style scoped>
	.card {
		background: var(--white);
		max-width: 700px;
		display: flex;
		flex-direction: column;
		border-radius: 10px;
		box-shadow: 0 0 15px var(--grayishBlue);
		margin: 0 30px;
	}
</style>
