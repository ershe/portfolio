<template>
	<main class="w-full h-screen dark:bg-gray-900">
		<TheHeader></TheHeader>
		<ViewHome></ViewHome>
	</main>
</template>

<script setup>
	import ViewHome from './views/ViewHome.vue';
	import TheHeader from './components/TheHeader.vue';
</script>
