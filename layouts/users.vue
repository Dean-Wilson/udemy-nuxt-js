<template>
	<div>
		<Header />
		<h2>Users Section</h2>
		<Nuxt />
	</div>
</template>

<script>
import Header from '@/components/Header.vue'

export default {
	components: {
		Header
	}
}
</script>

<style>
	body {
		font-family: arial;
	}
</style>