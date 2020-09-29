<template>
	<div id="app" class="app">
		<Header />
		<div class="app__content">
			<router-view />
		</div>
	</div>
</template>

<script>
import Header from "@/components/Header";

export default {
	components: {
		Header,
	},
};
</script>

<style lang="scss">
	.app {
		font-family: "Roboto", Helvetica, Arial, sans-serif;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
		height: 100%;
		height: 100vh;
		font-size: 16px;
		overflow-y: scroll;

		&__content {
			width: 100%;
			display: flex;
			justify-content: center;
			align-items: center;
			padding-top: 10px + $header-height;
			color: $text-primary;
		}
	}
</style>
