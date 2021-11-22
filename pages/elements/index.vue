<template>
	<main class="main">
		<h1 class="d-none">Funny Vue eCommerce Template</h1>

		<div class="page-content">
			<element-list></element-list>
		</div>
	</main>
</template>

<script>
import ElementList from '~/components/partials/elements/ElementList';

export default {
	components: {
		ElementList
	}
}
</script>