<script>
import AppContent from "./components/AppContent.vue";
import AppFooter from "./components/AppFooter.vue";
import AppHeader from "./components/AppHeader.vue";
export default {
	components: {AppHeader, AppContent, AppFooter},
};
</script>

<template>
	<AppHeader>
		<div class="container"></div>
	</AppHeader>

	<AppContent> </AppContent>

	<AppFooter> </AppFooter>
</template>

<style lang="scss">
$blue: #0282f9;
$darkgrey: #303030;
$lightgrey: #808080;
$grey: #353535;
</style>
