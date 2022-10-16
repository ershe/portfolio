<template>
	<div><h1>Portfolio</h1></div>
	<BaseGrid>
		<BaseCard
			v-for="galItem in galItems"
			:key="galItem.id"
			:card-src="galItem.cardSrc"
			:card-title="galItem.cardTitle"
			:card-description="galItem.cardDescription"
		>
		</BaseCard>
	</BaseGrid>
</template>

<script setup>
	import { ref } from 'vue';
	import BaseGrid from '../components/BaseGrid.vue';
	import BaseCard from '../components/BaseCard.vue';

	const galItems = ref([
		{
			id: '1',
			cardSrc:
				'https://images.unsplash.com/photo-1663928958939-2ed7395177a7?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1035&q=80',
			cardTitle: 'title i',
			cardDescription: 'description i',
		},
		{
			id: '2',
			cardSrc:
				'https://images.unsplash.com/photo-1663961355715-cf362778dc0e?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1035&q=80',
			cardTitle: 'title ii',
			cardDescription: 'description ii',
		},
		{
			id: '3',
			cardSrc:
				'https://images.unsplash.com/photo-1653140443525-ef681e06d601?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1035&q=80',
			cardTitle: 'title iii',
			cardDescription: 'description iii',
		},
		{
			id: '4',
			cardSrc:
				'https://images.unsplash.com/photo-1663928958939-2ed7395177a7?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1035&q=80',
			cardTitle: 'title i',
			cardDescription: 'description i',
		},
		{
			id: '5',
			cardSrc:
				'https://images.unsplash.com/photo-1663961355715-cf362778dc0e?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1035&q=80',
			cardTitle: 'title ii',
			cardDescription: 'description ii',
		},
		{
			id: '6',
			cardSrc:
				'https://images.unsplash.com/photo-1653140443525-ef681e06d601?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1035&q=80',
			cardTitle: 'title iii',
			cardDescription: 'description iii',
		},
	]);
</script>

<style lang="scss" scoped></style>
