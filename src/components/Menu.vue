<script>

</script>

<template>
<div class="menu_wrapper">
	<h1>.mathiasbolle</h1>
	<nav>
		<menu>
			<li>highlights</li>
			<li>about me</li>
			<li>projects</li>
			<li>contact</li>
		</menu>
	</nav>
</div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Inconsolata&family=Sura:wght@700&display=swap');
	.menu_wrapper {
		width: 100%;
		display: flex;
		color: white;
		background-color: #292c3c;
		padding-top: 0.5em;
	}


	menu {
		display: flex;
		margin-left: auto;
	}
	h1, menu {
		font-family: 'Inconsolata', monospace;
		font-size: large;
		margin-bottom: 0%; /*fix with a general css rule? */
	}

	menu {
		list-style: none;
		font-size: large;
	}
</style>
