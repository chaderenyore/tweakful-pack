<template>
	<section class="container benefits-section-1">
		<div class="benefit-wrapper is-flex">
			<section class="benefit-lists">
				<div class="benefit-list benefit-list-1 is-flex is-align-items-flex-start">
					<div class="benefit-list-icon">
						<img src="../assets/benefit-list-1.svg">
					</div>
					<div class="benefit-list-text">
						<h3>First Benefit</h3>
						<p>Gorgeous, high-quality design system for mobile, tablet & desktop devices a few </p>
					</div>
				</div>
				<div class="benefit-list benefit-list-2 is-flex is-align-items-flex-start">
					<div class="benefit-list-icon">
						<img src="../assets/benefit-list-2.svg">
					</div>
					<div class="benefit-list-text">
						<h3>Second Benefit</h3>
						<p>Gorgeous, high-quality design system for mobile, tablet & desktop devices a few</p>
					</div>
				</div>
				<div class="benefit-list benefit-list-3 is-flex is-align-items-flex-start">
					<div class="benefit-list-icon">
						<img src="../assets/benefit-list-3.svg">
					</div>
					<div class="benefit-list-text">
						<h3>Third Benefit</h3>
						<p>Gorgeous, high-quality design system for mobile, tablet & desktop devices a few</p>
					</div>
				</div>
			</section>
			<article class="benefit-cta">
				<h1 class="benefit-cta-h1">
					Headline of Modern and Digital Lending Platform Seconds
				</h1>
				<p class="benefit-cta-p">
					Nowadays, it isn’t uncommon to see lenders rapidly adopting a digital lending strategy
				</p>
				<a class="benefit-cta-button">
					Learn More About <img src="../assets/long_right.svg" alt="" style="margin-left: 8px;">
				</a>
			</article>
		</div>
	</section>

	<section class="container benefits-section-2">
		<div class="benefit-wrapper">
		<h1 class="section-2-heading">
			Benefits of working with us
		</h1>
		<div class="benefit-grids">
			<div class="benefit-list benefit-grid-1 is-flex is-align-items-flex-start">
					<div class="benefit-grid-icon">
						<img src="../assets/feature-icons/01.svg">
					</div>
					<div class="benefit-list-text">
						<h3>Time zones ain’t no thing</h3>
						<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mattis et sed nam sem tellus erat.</p>
					</div>
				</div>

				<div class="benefit-list benefit-grid-2 is-flex is-align-items-flex-start">
					<div class="benefit-grid-icon">
						<img src="../assets/feature-icons/04.svg">
					</div>
					<div class="benefit-list-text">
						<h3>Full spectrum of services</h3>
						<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mattis et sed nam sem tellus erat.</p>
					</div>
				</div>

				<div class="benefit-list benefit-grid-3 is-flex is-align-items-flex-start">
					<div class="benefit-grid-icon">
						<img src="../assets/feature-icons/Group.svg">
					</div>
					<div class="benefit-list-text">
						<h3>Impossible? We’re on it</h3>
						<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mattis et sed nam sem tellus erat.</p>
					</div>
				</div>

				<div class="benefit-list benefit-grid-4 is-flex is-align-items-flex-start">
					<div class="benefit-grid-icon">
						<img src="../assets/feature-icons/07.svg">
					</div>
					<div class="benefit-list-text">
						<h3>Flexible work terms</h3>
						<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mattis et sed nam sem tellus erat.</p>
					</div>
				</div>
		</div>
		</div>
	</section>
</template>

<style scoped>
	.benefits-section-1 {
		margin-top: 9rem;
		margin-bottom: 11rem;
	}

	.benefit-wrapper {
		gap: 8px;
		width: 95%;
		margin: 0 auto;
	}

	.benefit-lists {
		width: 48%;
	}

	.benefit-list {
		width: 100%;
	}

	.benefit-list {
		gap: 20px;
	}

	.benefit-list-2, 
	.benefit-list-3 {
		margin-top: 2.5rem;
	}

	.benefit-list-icon,
	.benefit-grid-icon {
		background: var(--bg-secondary);
		display: flex;
		align-items: center;
		justify-content: center;
		border-radius: 50%;
	}

	.benefit-list-icon {
		padding: .8rem;
	}

	.benefit-grid-icon {
		padding: 1.4rem;
	}

	.benefit-list-text h3 { 
		color: var(--text-primary);
		font-weight: 700;
		font-size: 1.18rem;
	 }

	 .benefit-list-text p {
	 	width: 84%;
	 	color: var(--text-secondary);
	 	margin-top: 6px;
	 }

	 .benefit-cta {
	 	width: 44%;
	 }

	 .benefit-cta-h1 {
	 	font-size: 2.6rem;
	 	line-height: 1.4;
	 	font-weight: 700;
	 	font-family: 'Inter', sans-serif;
	 	color: var(--text-primary);
	 	margin-bottom: 1rem;
	 	/*width: 89%;*/
	 }

	 .benefit-cta-p {
	 	width: 87%;
	 	line-height: 1.6;
	 	margin-bottom: 1rem;
	 }

	 
	.benefit-cta-button {
		display: inline-block;
		background: var(--button-primary);
	    color: white;
	    border-radius: 1px;
	    padding: 15px 25px;
	    margin-top: .8rem;
	}

	.benefits-section-2 {
		margin-top: 7rem;
	}

	.section-2-heading {
		font-weight: 700;
		font-size: 2rem;
		color: var(--text-gray);
	}

	.benefit-grids {
		margin-top: 2rem;
		display: grid;
		grid-template-columns: auto auto;
		grid-template-rows: auto auto;
		grid-row-gap: 2rem;

	}
</style>