<template>
	<div class="process-wrapper container">
		<div class="process-box">
			<h1 class="process-box__h1">The Process We Follow</h1>
			<div class="processes">
				<div class="processes-1">
					<img src="../assets/Indication.svg">
					<h1 class="process-name">Ideate</h1>
					<p>Turn your idea from concept to MVP</p>
				</div>

				<div class="processes-2">
					<img src="../assets/Indication.svg">
					<h1 class="process-name">Design</h1>
					<p>Sketch out the product to align the user needs</p>
				</div>

				<div class="processes-3">
					<img src="../assets/Indication.svg">
					<h1 class="process-name">Develop</h1>
					<p>Convert the designs into a live application</p>
				</div>

				<div class="processes-4">
					<h1 class="process-name">Deploy</h1>
					<p>Launching the application to the market</p>
				</div>
				
			</div>
		</div>
	</div>
</template>

<style scoped>
	.process-box {
		width: 90%;
		margin: auto;
		margin-bottom: 4rem;
	}

	.process-box__h1 {
		font-size: 1.4rem;
		color: var(--text-gray);
		font-family: 'Inter' sans-serif;
		font-weight: 700;
	} 

	.processes {
		display: flex;
		margin-top: 2rem;
		gap: .8rem;
	}

	.processes-4 {
		margin-top: 1.1rem;
		align-self: center;
	}

	.process-name {
		font-weight: 700;
		font-size: 1.1rem;
		color: var(--text-primary);
		margin-bottom: .4rem;
	}

</style>