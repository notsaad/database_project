<script>
	import Button from '../components/Button.svelte';
</script>

<svelte:head>
	<title>Hotel Booker</title>
	<meta name="Hotel Booker" content="Svelte Site for Hotel Booking" />
</svelte:head>

<section>
	<h1>
		Hotel Booking Site
	</h1>

	<h2>
		I am a:
	</h2>

	<a class="button" href="/user">User</a>
	<a class="button" href="/employee">Employee</a>

</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	h1 {
		width: 100%;
	}

</style>
