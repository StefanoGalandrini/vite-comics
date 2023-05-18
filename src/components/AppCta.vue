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
$color-blue: #0282f9;
$color-lightgrey: #808080;
$color-grey: #353535;
.container {
	height: 13vh;
	background-color: $color-grey;
	color: white;
}
.cta {
	height: 100%;
	max-width: 70vw;
	margin-inline: auto;
	display: flex;
	justify-content: space-between;
	align-items: center;

	button {
		border: 2px solid $color-blue;
		padding: 0.8rem 1.2rem;
		font-size: 1.2rem;
		text-transform: uppercase;
		color: white;
		background-color: $color-grey;
	}

	.socials {
		display: flex;
		align-items: center;
	}
	.text {
		display: inline-block;
		color: $color-blue;
		font-family: "Encode Sans Condensed";
		text-transform: uppercase;
		font-size: 1.5rem;
	}

	.icon {
		display: inline-block;
		width: 2.5rem;
		height: 2.5rem;
		background-color: $color-lightgrey;
		border-radius: 50%;
		overflow: hidden;
		margin-left: 1rem;
		position: relative;
	}

	i {
		font-size: 1.5rem;
		color: $color-grey;
		background-color: $color-lightgrey;
		position: absolute;
		top: 50%;
		left: 50%;
		transform: translate(-50%, -50%);
	}
}
</style>
