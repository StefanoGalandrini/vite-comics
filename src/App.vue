<script>
import AppContent from "./components/AppContent.vue";
import AppCta from "./components/AppCta.vue";
import AppFooter from "./components/AppFooter.vue";
import AppHeader from "./components/AppHeader.vue";
import AppIcons from "./components/AppIcons.vue";
export default {
	components: {AppHeader, AppContent, AppFooter, AppIcons, AppCta},
};
</script>

<template>
	<AppHeader />

	<AppContent />

	<AppIcons />

	<AppFooter />
</template>

<style lang="scss">
@use "./assets/styles/general.scss" as *;
@import url("https://fonts.googleapis.com/css2?family=Encode+Sans+Condensed:wght@600&family=Open+Sans:wght@300;400;600&display=swap");

*,
*::before,
*::after {
	margin: 0;
	padding: 0;
	box-sizing: border-box;
}

:root {
	font-family: "Encode Sans Condensed", sans-serif;
	font-family: "Open Sans", sans-serif;
}
</style>
