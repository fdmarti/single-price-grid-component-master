<template>
	<section class="subscription">
		<h2>Monthly Subscription</h2>
		<p>
			<span><strong>&dollar;29</strong> per month</span>
		</p>
		<p>Full access for less than &dollar;1 a day</p>
		<button>Sign Up</button>
	</section>
</template>
<style scoped>
	.subscription {
		display: flex;
		flex-direction: column;
		gap: 1rem;
		padding: 30px;
		width: 50%;
		background-color: var(--cyan);
		border-bottom-left-radius: 5px;
	}

	h2 {
		font-size: 18px;
	}

	span {
		display: flex;
		align-items: center;
		gap: 1rem;
		color: var(--grayishBackground);
	}

	strong {
		font-size: 36px;
	}

	button {
		border: none;
		border-radius: 5px;
		padding: 15px;
		max-width: 200px;
		background-color: var(--brightYellow);
		color: var(--white);
		font-size: 18px;
		font-weight: 700;
		box-shadow: 0 0 15px -7px #000;
	}

	button:hover {
		cursor: pointer;
		background-color: var(--brightYellowHover);
	}

	@media (max-width: 600px) {
		.subscription {
			width: 100%;
			padding: 30px 0;
			text-align: center;
			border-bottom-left-radius: 0;
		}

		span {
			justify-content: center;
		}

		button {
			margin: 0 auto;
			width: 300px;
		}
	}
</style>
