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
		<main>{{ content }}</main>
	</div>
</template>

<style lang="scss" scoped>
$color-darkgrey: #303030;
.container {
	height: 13vh;
	background-color: $color-darkgrey;
}

main {
	max-width: 70vw;
	margin-inline: auto;
	color: white;
}
</style>
