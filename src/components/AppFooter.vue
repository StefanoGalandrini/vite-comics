<script>
import AppCta from "./AppCta.vue";
import AppIcons from "./AppIcons.vue";

export default {components: {AppIcons, AppCta}};
</script>

<template>
	<div class="container">
		<AppIcons></AppIcons>
		<footer></footer>
		<AppCta></AppCta>
	</div>
</template>

<style lang="scss" scoped>
.container {
	height: 80vh;
	background-color: $grey;
}

footer {
	height: 57vh;
	background-image: url(../assets/img/footer-bg.jpg);
	background-size: cover;
	background-position: center center;
}
</style>
