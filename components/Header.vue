<template>
	<header class="header">
		<ul class="nav">
			<li class="nav__item">
				<nuxt-link class="nav__link" to="/">Home</nuxt-link>
			</li>
			<li class="nav__item">
				<nuxt-link class="nav__link" to="/users">Users</nuxt-link>
			</li>
			<li class="nav__item">
				<nuxt-link class="nav__link" to="/products">Products</nuxt-link>
			</li>
		</ul>
	</header>
</template>

<script>
export default {

}
</script>

<style scoped>
	.header {
		width: 100%;
		background-color: #eeeeee;
		padding: 15px;
	}
	.nav {
		list-style: none;
		display: flex;
		
	}
	.nav__item {
		margin-right: 10px;
	}
	.nav__link {
		color: #1f1f1f;
	}
	.nav__link:hover {
		text-decoration: none;
	}
</style>