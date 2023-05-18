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
$color-darkgrey: #303030;
.container {
	height: 13vh;
	background-color: $color-darkgrey;
}

main {
	max-width: 70vw;
	height: 100%;
	margin-inline: auto;
	color: white;

	.content {
		height: 100%;
		display: flex;
		justify-content: flex-start;
		align-items: center;
		font-size: 1.2rem;
		font-weight: bold;
	}
}
</style>
