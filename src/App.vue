<script setup>
import Analytics from './components/Analytics.vue'
import Header from './components/Header.vue'
import Platform from './components/Platform.vue'
import Services from './components/Services.vue'
</script>

<template>
	<div class="app">
		<Header></Header>
		<Platform></Platform>
		<Services></Services>
		<Analytics></Analytics>
	</div>
</template>

<style scoped>
.app {
	font-family: 'Golos Text', serif;
	color: #000;
}
</style>
