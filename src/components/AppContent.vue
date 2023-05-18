<script>
export default {
	data() {
		return {
			content: "--> Content goes Here <--",
		};
	},
};
</script>

<template>
	<div class="container">
		<main>
			<div class="content">
				{{ content }}
			</div>
		</main>
	</div>
</template>

<style lang="scss" scoped>
@use "../assets/styles/partials/contents" as *;

.container {
	height: 13vh;
	background-color: $color-darkgrey;
}
</style>
