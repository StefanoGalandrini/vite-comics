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
$color-darkgrey: #303030;
$color-blue: #0282f9;
.container {
	height: 13vh;
	background-color: white;
	color: $color-darkgrey;
}

.top-bar {
	height: 100%;
	max-width: 70vw;
	margin-inline: auto;
	display: flex;
	justify-content: flex-end;
	align-items: center;

	img {
		width: 80px;
		aspect-ratio: 1 / 1;
		object-fit: cover;
		margin-right: auto;
	}
}

nav {
	height: 100%;
}
.menu {
	height: 100%;
	list-style-type: none;
	display: flex;
}
.item {
	display: flex;
	height: 100%;
	align-items: center;
	margin-left: 1.5rem;
	font-family: "Encode Sans Condensed";
	text-decoration: none;
	text-transform: uppercase;
	border-bottom: 5px solid rgba(255, 255, 255, 0);
	color: $color-darkgrey;

	&:hover {
		color: $color-blue;
	}
}

.active {
	color: $color-blue;
	border-bottom: 5px solid $color-blue;
}
</style>
