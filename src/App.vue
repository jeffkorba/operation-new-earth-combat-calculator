<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>

	<section class="container">

		<header>

			<div class="wrapper">

				<nav>

					<RouterLink to="/">Home</RouterLink>

				</nav>

			</div>

		</header>

		<section>

			<form>


				<h3>Offensive Research</h3>

				<div class="row">


				
					<div class="col">
						<input type="number" class="form-control" id="attack" placeholder="Attack" />
					</div>

					<div class="col">
						<input type="number" class="form-control" id="defense" placeholder="Defense" />
					</div>

					<div class="col">
						<input type="number" class="form-control" id="health" placeholder="Health" />
					</div>
				
				</div>

				<h3>Efficiency Research</h3>

			</form>

		</section>

		<RouterView />

	</section>

</template>

<style scoped>
header {

}
</style>