<script>
export default {};
</script>

<template>
	<div class="container">
		<div class="content">
			<div class="item">
				<img src="../assets/img/buy-comics-digital-comics.png" alt="" />
				<span>digital comics</span>
			</div>
			<div class="item">
				<img src="../assets/img/buy-comics-merchandise.png" alt="" />
				<span>dc merchandise</span>
			</div>
			<div class="item">
				<img src="../assets/img/buy-comics-subscriptions.png" alt="" />
				<span>subscription</span>
			</div>
			<div class="item">
				<img src="../assets/img/buy-comics-shop-locator.png" alt="" />
				<span>comic shop locator</span>
			</div>
			<div class="item">
				<img src="../assets/img/buy-dc-power-visa.svg" alt="" />
				<span>digital comics</span>
			</div>
		</div>
	</div>
</template>

<style lang="scss" scoped>
$color-blue: #0282f9;
.container {
	height: 16vh;
	color: white;
	background-color: $color-blue;
}

.content {
	height: 100%;
	max-width: 70vw;
	margin-inline: auto;
	display: flex;
	justify-content: center;
	align-items: center;
	gap: 2rem;

	.item {
		height: 100%;
		display: flex;
		justify-content: center;
		align-items: center;

		img {
			max-width: 30%;
			height: 40%;
			margin-right: 1rem;
		}

		span {
			font-size: 0.9rem;
			text-transform: uppercase;
			white-space: nowrap;
		}
	}
}
</style>
