<template>
  <div>
	<!-- This is a wrapper for /users -->
    <input type="text" v-model="userId" />
    <button @click="goToUser">Load User</button>
	<nuxt-child />
  </div>
</template>

<script>
export default {
	data() {
		return {
			userId: ''
		}
	},
	methods: {
		goToUser() {
			this.$router.push('/users/' + this.userId)
		}
	},
	layout: 'users'
}
</script>