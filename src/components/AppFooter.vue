<script>
import AppCta from "./AppCta.vue";
export default {
	components: {AppCta},
};
</script>

<template>
	<div class="container">
		<footer>
			<div class="links">
				<ul class="first">
					<li class="title">DC COMICS</li>
					<li><a href="#">Characters</a></li>
					<li><a href="#">Comics</a></li>
					<li><a href="#">Movies</a></li>
					<li><a href="#">TV</a></li>
					<li><a href="#">Games</a></li>
					<li><a href="#">Videos</a></li>
					<li><a href="#">News</a></li>

					<li class="last-title">SHOP</li>
					<li><a href="#">Shop DC</a></li>
					<li><a href="#">Shop DC Collectibles</a></li>
				</ul>

				<ul>
					<li class="title">DC</li>
					<li><a href="#">Terms Of Use</a></li>
					<li><a href="#">Privacy policy (New)</a></li>
					<li><a href="#">Ad Choiches</a></li>
					<li><a href="#">Advertising</a></li>
					<li><a href="#">jobs</a></li>
					<li><a href="#">Subscriptions</a></li>
					<li><a href="#">Talent Workshops</a></li>
					<li><a href="#">CPSC Certificates</a></li>
					<li><a href="#">Ratings</a></li>
					<li><a href="#">Shop Help</a></li>
					<li><a href="#">Contact Us</a></li>
				</ul>

				<ul>
					<li class="title">SITES</li>
					<li><a href="#">DC</a></li>
					<li><a href="#">MAD Magazine</a></li>
					<li><a href="#">DC Kids</a></li>
					<li><a href="#">DC Universe</a></li>
					<li><a href="#">DC Power Visa</a></li>
				</ul>
			</div>
			<div class="logo">
				<img src="../assets/img/dc-logo-bg.png" alt="" />
			</div>
		</footer>
	</div>

	<AppCta></AppCta>
</template>

<style lang="scss" scoped>
@use "../assets/styles/partials/footer" as *;

.container {
	height: 45vh;
	background-color: $color-grey;
	background-image: url(../assets/img/footer-bg.jpg);
	background-size: cover;
	background-position: center center;
}
</style>
