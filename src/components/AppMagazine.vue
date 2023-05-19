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
		price: {
			type: String,
			required: false,
		},
	},
};
</script>

<template>
	<div class="comic">
		<img :src="cover" alt="Cover" />
		<p class="title">{{ title }}</p>
	</div>
</template>

<style lang="scss" scoped>
.comic {
	width: 15%;
	height: 20%;

	img {
		width: 100%;
		aspect-ratio: 1 / 1;
		object-fit: cover;
		object-position: top center;
		overflow: hidden;
	}
}
</style>
