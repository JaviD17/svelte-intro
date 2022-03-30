<script>
	import Title from '$lib/title.svelte';

	// let title = 'ReFlow';

	// const updateTitle = () => {
	// 	title = 'ReFlow 2.0';
	// };
</script>

<svelte:head>
	<title>ReFlow</title>
</svelte:head>

<Title />

<div class="index">
	<p>
		Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
		labore et dolore magna aliqua. Id porta nibh venenatis cras sed felis. Libero volutpat sed cras
		ornare arcu dui. Egestas maecenas pharetra convallis posuere morbi. Faucibus turpis in eu mi
		bibendum neque egestas. Diam maecenas sed enim ut sem. Ac turpis egestas sed tempus urna et
		pharetra pharetra massa. Et molestie ac feugiat sed lectus vestibulum. Amet dictum sit amet
		justo donec enim. Tellus in metus vulputate eu scelerisque felis imperdiet proin. A iaculis at
		erat pellentesque. Eget sit amet tellus cras adipiscing enim eu turpis egestas. Nulla porttitor
		massa id neque aliquam vestibulum morbi blandit. Egestas maecenas pharetra convallis posuere.
		Donec pretium vulputate sapien nec. Commodo viverra maecenas accumsan lacus vel facilisis.
	</p>

	<!-- <button on:click={updateTitle}>Change Title</button>

    <input type='text' bind:value={title}> -->

	<a href="/guides">View guides</a>
	<a href="/about">About</a>
</div>

<style>
	.index {
		text-align: center;
		display: block;
		margin: 20px auto;
	}
</style>
