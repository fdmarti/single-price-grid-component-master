<template>
	<section class="banner">
		<h1>Join our community</h1>
		<p class="days">30-day, hassle-free money back guarantee</p>
		<p class="info">
			Gain access to our full library of tutorials along with expert code
			reviews. Perfect for any developers who are serious about honing their
			skills.
		</p>
	</section>
</template>
<style scoped>
	.banner {
		display: flex;
		flex-direction: column;
		gap: 1rem;
		margin-bottom: 30px;
		padding: 50px;
		padding-bottom: 0;
	}

	h1 {
		color: var(--cyan);
	}

	.days {
		color: var(--brightYellow);
		font-size: 19px;
		font-weight: 700;
	}

    .info {
        color: var(--grayishBlue);
    }
</style>
