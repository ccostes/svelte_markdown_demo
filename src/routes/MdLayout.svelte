<!-- Layout to use frontmatter titles as page title -->
<script>
	export let title;
</script>

<svelte:head>
	<title>{title}</title>
</svelte:head>

<slot></slot>