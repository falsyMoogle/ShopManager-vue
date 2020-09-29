<template>
	<header class="header">
		<div class="header__brand">
			<span class="icon-btn icon-btn--primary">
				<i class="fas fa-bars"></i>
			</span>
			<h2>Shopify</h2>
		</div>
		<span class="btn btn--primary">User</span>
	</header>
</template>

<script>
export default {
	name: "Header",
};
</script>

<style lang="scss">
	.header {
		position: absolute;
		top: 0;
		left: 0;
		right: 0;
		height: $header-height;
		display: flex;
		justify-content: space-between;
		padding: 0 1rem;
		align-items: center;
		background: $primary-dark;
		color: $text-light;
		z-index: 100;

		&__brand {
			display: flex;

			& span {
				background: $primary-dark;
				margin-right: 2rem;
				@include hover-dark($primary-dark);
				& i {
					color: $text-light;
				}
			}
		}
	}
</style>>