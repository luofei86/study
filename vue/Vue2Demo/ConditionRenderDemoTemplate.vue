<template v-if='loginType ==== "userName"'>
	<label>Username</label>
	<input placeholder="Enter your username" key="username-input">
</template>
<template v-else>
	<label>Email</label>
	<input placeholder="Enter your email" key="email">
</template>

<script>
	export default{
		name: 'crdt',
		props: {
			loginType: String
		}
	}
</script>

<style>
</style>