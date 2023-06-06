<template>
	<section class="why-us">
		<h2>Why Us</h2>
		<p>
			Tutorials by industry experts Peer &amp; expert code review Coding
			exercises Access to our GitHub repos Community forum Flashcard decks New
			videos every week
		</p>
	</section>
</template>
<style scoped>
	.why-us {
		display: flex;
		flex-direction: column;
		gap: 1.5rem;
		background-color: var(--cyanLighter);
		width: 50%;
		padding: 30px;
		border-bottom-right-radius: 5px;
	}

	h2 {
		font-size: 18px;
	}

	p {
		max-width: 250px;
		color: var(--grayishBackground);
	}

	@media (max-width: 600px) {
		.why-us {
			width: 100%;
			padding: 30px 0;
			text-align: center;
			border-bottom-left-radius: 5px;
		}

		p {
			max-width: fit-content;
			padding: 0 20px;
		}
	}
</style>
