<script>
export default {};
</script>

<template>
	<div class="container">
		<footer>Footer links</footer>
	</div>
</template>

<style lang="scss" scoped>
$color-grey: #353535;
.container {
	height: 45vh;
	background-color: $color-grey;
	background-image: url(../assets/img/footer-bg.jpg);
	background-size: cover;
	background-position: center center;
}

footer {
	max-width: 70vw;
	margin-inline: auto;
	color: white;
}
</style>
