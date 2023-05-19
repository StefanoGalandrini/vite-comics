<script>
export default {
	props: {
		title: {
			type: String,
			required: true,
		},
		cover: {
			type: String,
			required: true,
		},
	},
};
</script>

<template>
	<div class="magazine">
		<img :src="cover" alt="" />
		<p class="title">{{ title }}</p>
	</div>
</template>

<style lang="scss" scoped>
.magazine {
	display: flex;
	flex-direction: column;
	align-items: start;
	gap: 1rem;

	img {
		width: 100%;
		aspect-ratio: 1 / 1;
		overflow: hidden;
		object-fit: cover;
		object-position: top center;
	}

	.title {
		font-family: "Encode Sans Condensed", sans-serif;
		text-transform: uppercase;
		font-size: 0.8rem;
		margin-bottom: 1rem;
	}
}
</style>
