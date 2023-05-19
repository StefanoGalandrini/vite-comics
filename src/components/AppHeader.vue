<script>
export default {
	data() {
		return {
			menuItems: [
				{
					item: "characters",
					isActive: false,
				},
				{
					item: "comics",
					isActive: false,
				},
				{
					item: "movies",
					isActive: false,
				},
				{
					item: "tv",
					isActive: false,
				},
				{
					item: "games",
					isActive: false,
				},
				{
					item: "collectibles",
					isActive: false,
				},
				{
					item: "videos",
					isActive: false,
				},
				{
					item: "fans",
					isActive: false,
				},
				{
					item: "news",
					isActive: false,
				},
				{
					item: "shop",
					isActive: false,
				},
			],
		};
	},
	methods: {
		toggleActive(item) {
			for (let i = 0; i < this.menuItems.length; i++) {
				this.menuItems[i].isActive = false;
			}
			item.isActive = !item.isActive;
		},
	},
};
</script>

<template>
	<div class="container">
		<div class="top-bar">
			<img
				src="../assets/img/dc-logo.png"
				alt="Logo DC" />
			<nav>
				<ul class="menu">
					<li v-for="menuItem in menuItems">
						<a
							href="#"
							class="item"
							:class="{active: menuItem.isActive}"
							@click="toggleActive(menuItem)">
							{{ menuItem.item }}
						</a>
					</li>
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
