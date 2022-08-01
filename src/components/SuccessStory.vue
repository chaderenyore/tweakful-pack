<template>
	<div class="success-wrapper container">
		<div class="story-box">
			<div class="story-box__texts">
				<h1 class="story-box__texts--h1">Success Story</h1>
				<p class="story-box__texts--p">
					Nowadays, it isn’t uncommon to see lenders rapidly adopting a digital lending strategy to streamline the lending process
				</p>
				<div class="story-box__texts--brand">
					<img src="../assets/Brands/Logitech.svg">
				</div>
				<div class="story-box__texts--read">
					<p>Read Complete Case Study <img src="../assets/long_right-blue.svg" alt="" style="margin-left: 0.8em;"></p>
				</div>
			</div>
			<div class="story-box__image">
				<img src="../assets/reviewer.svg" alt="Woman Case Study">
			</div>
		</div>
	</div>
</template>

<style scoped>
	.success-wrapper {
		margin-top: 13rem;
		margin-bottom: 11rem;
	}

	.story-box {
		width: 90%;
		margin: auto;
		background: var(--bg-secondary);
		display: flex;
		padding: 6rem 0 6rem 6rem;
	}

	.story-box__texts {
		display: flex;
		flex-direction: column;
	}

	.story-box__texts--h1 {
		font-size: 1.8rem;
	 	line-height: 1.4;
	 	font-weight: 700;
	 	font-family: 'Inter', sans-serif;
	 	color: var(--text-primary);
	 	margin-bottom: .9rem;
	}

	.story-box__texts--p {
		font-size: 1.8rem;
	 	line-height: 1.6;
	 	font-weight: 400;
	 	width: 75%;
	 	font-family: 'Inter', sans-serif;
	 	color: var(--text-primary);
	 	display: inline-block;
	 	margin-bottom: 1.4rem;
	}

	.story-box__texts--read {
		color: var(--blue-primary);
		cursor: pointer;
		align-self: baseline;
	}

	.story-box__image {
		flex-basis: 90%;
	}

	.story-box__image img {
		height: 100%;
		width: 100%;
	}
</style>