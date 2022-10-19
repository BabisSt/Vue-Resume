<template>
	<header class="row text-center">
		<div class="col">
			<router-link class="p-4 mylink btn btn-block index" to="/">Home</router-link>
		</div>
		<div class="col">
			<router-link class="p-4 mylink btn btn-block index" to="/experience">Experience</router-link>
		</div>
		<div class="col">
			<router-link class="p-4 mylink btn btn-block index" to="/skills">Skills</router-link>
		</div>
		<div class="col">
			<router-link class="p-4 mylink btn btn-block index" to="/projects">Projects</router-link>
		</div>

	</header>
</template>

<script>
export default {
	name: 'Header',

}
</script>

<style  >
.btn {
	color: aliceblue !important;
}

.btn:hover {
	color: #042A3B !important;
	background-color: aliceblue !important;
}

header {
	background-color: #042A3B;

}

.index{
	z-index: 999;
}
</style>