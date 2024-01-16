<script lang="ts">
	import Header from './header.svelte'
	import Footer from './footer.svelte'

	import 'open-props/style'
	import 'open-props/normalize'
	import 'open-props/buttons'
</script>

<div class="layout">
	<Header />

	<main>
		<slot />
	</main>

	<Footer />
</div>

<style>
	.layout {
		height: 100%;
		/* max-width also works */
		/* max-inline-size: 1440px; */
		max-width: 1440px;
		display: grid;
		grid-template-columns: auto 1fr auto;
		/* margin: 0 auto */
		margin-inline: auto;
		padding-inline: var(--size-7);
	}
</style>
