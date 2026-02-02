<script lang="ts">
	import Sidebar from '$lib/components/sidebar.svelte';
</script>

<div class="container flex min-h-screen">
	<Sidebar />

	<slot />
</div>
