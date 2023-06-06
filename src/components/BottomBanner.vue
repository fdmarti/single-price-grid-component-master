<template>
	<section class="bottom-banner">
		<Subscription />
		<WhyUs />
	</section>
</template>
<script setup>
	import Subscription from './BottomBanner/Subscription.vue';
	import WhyUs from './BottomBanner/WhyUs.vue';
</script>
<style scoped>
	.bottom-banner {
		display: flex;
		color: var(--lightGray);
	}

	@media (max-width: 600px) {
		.bottom-banner {
			flex-direction: column;
		}
	}
</style>
