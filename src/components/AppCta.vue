<script>
export default {};
</script>

<template>
	<link
		rel="stylesheet"
		href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
		integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw=="
		crossorigin="anonymous"
		referrerpolicy="no-referrer" />
	<div class="container">
		<div class="cta">
			<button class="sign-up">SIGN UP NOW!</button>
			<div class="socials">
				<div class="text">follow us</div>
				<div class="icon">
					<i class="fa-brands fa-facebook-f"></i>
				</div>
				<div class="icon">
					<i class="fa-brands fa-twitter"></i>
				</div>
				<div class="icon">
					<i class="fa-brands fa-youtube"></i>
				</div>
				<div class="icon">
					<i class="fa-brands fa-pinterest-p"></i>
				</div>
				<div class="icon">
					<i class="fa-solid fa-location-dot"></i>
				</div>
			</div>
		</div>
	</div>
</template>

<style lang="scss" scoped>
@use "../assets/styles/partials/cta" as *;
.container {
	height: 13vh;
	background-color: $color-grey;
	color: white;
}
</style>
