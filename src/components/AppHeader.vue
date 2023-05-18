<script>
export default {};
</script>

<template>
	<div class="container">
		<div class="top-bar">
			<img src="../assets/img/dc-logo.png" alt="Logo DC" />
			<nav>
				<ul class="menu">
					<li><a class="item" href="#">characters</a></li>
					<li><a class="item active" href="#">comics</a></li>
					<li><a class="item" href="#">movies</a></li>
					<li><a class="item" href="#">TV</a></li>
					<li><a class="item" href="#">games</a></li>
					<li><a class="item" href="#">collectibles</a></li>
					<li><a class="item" href="#">videos</a></li>
					<li><a class="item" href="#">fans</a></li>
					<li><a class="item" href="#">news</a></li>
					<li><a class="item" href="#">shop</a></li>
				</ul>
			</nav>
		</div>
	</div>
</template>

<style lang="scss" scoped>
@use "../assets/styles/partials/header" as *;

.container {
	height: 13vh;
	background-color: white;
	color: $color-darkgrey;
}
</style>
