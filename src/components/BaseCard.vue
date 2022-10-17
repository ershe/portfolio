<template>
	<div class="max-w-sm overflow-hidden hover:shadow-lg">
		<img class="w-full" :src="cardSrc" alt="" />
		<div class="px-6 py-4">
			<div class="font-bold text-xl mb-2">{{ cardTitle }}</div>
			<p class="text-gray-700 text-base">
				{{ cardDescription }}
			</p>
		</div>
	</div>
</template>

<script setup>
	const props = defineProps({
		cardTitle: {
			type: String,
			required: true,
		},
		cardDescription: {
			type: String,
			required: true,
		},
		cardSrc: {
			type: String,
			required: true,
		},
	});
</script>

<style lang="scss" scoped></style>
