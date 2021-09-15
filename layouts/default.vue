<template>
  <div>
	<Header />
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