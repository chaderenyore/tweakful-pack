<template>
	<header>
		<nav class="columns is-justify-content-space-evenly is-align-items-center">
			<div class="nav-logo-container column is-narrow is-align-self-flex-end">
				<img class="nav-logo" src="../assets/Tweakful-Logo.svg">
			</div>
			<div class="nav-links-container column is-one-third">
				<div class="nav-link-links is-flex is-justify-content-space-evenly">
					<a class="nav-link" href="#">Home</a>
					<a class="nav-link" href="#">Features</a>
					<a class="nav-link" href="#">Pricing</a>
					<a class="nav-link" href="#">About Us</a>
					<a class="nav-link" href="#">Help</a>
				</div>
			</div>
			<div class="cta-container column is-narrow">
				<a class="nav-cta" href="#">Book A Meeting <img src="../assets/long_right.svg" alt="" style="margin-left: 8px;"></a>
			</div>
		</nav>
	</header>
</template>

<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup

</script>

<style scoped>
	header {
		margin-top: 1.2rem;
	}

	.nav-link {
		color: var(--text-primary);
	}

	.nav-cta {
		background: var(--button-primary);
		color: white;
		border-radius: 1px;
		padding: 5px 20px;
	}
</style>
