<template>
	<div class="home">
		<h1>Home</h1>
		<hr />
		<div class="test">
			<span class="icon-btn">
				<i class="fas fa-bars"></i>
			</span>
			<router-link to="/" class="btn">Login</router-link>
			<router-link to="/" class="btn btn--lg">Login</router-link>
		</div>
	</div>
</template>

<script>
export default {
	name: "Home",
	components: {},
};
</script>

<style lang="scss">
	.home {
		width: 100%;
		padding: 1rem;
	}

	.test {
		display: flex;
		flex-direction: column;
		justify-content: space-around;
		align-items: center;
		height: 500px;
	}
</style>