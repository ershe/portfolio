<template>
	<main class="w-full h-full dark:bg-gray-900">
		<div class="container mx-auto">
			<TheHeader></TheHeader>
			<ViewHome></ViewHome>
		</div>
	</main>
</template>

<script setup>
	import ViewHome from './views/ViewHome.vue';
	import TheHeader from './components/TheHeader.vue';
</script>
