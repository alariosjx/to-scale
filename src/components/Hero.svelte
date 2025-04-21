<script>
	import Hero from "$components/helpers/Hero.svelte";

	/* 
		The Hero component is a full-width image or video with a headline, dek, and byline (these are optional).
		- hed: The headline for the hero.
		- dek: The dek for the hero.
		- byline: The byline for the hero.
		- src: The source of the image or video file.
		- alt: The alt text, if it's an image.
	*/
</script>

<Hero
	hed="To Scale"
	dek="Putting the world in perspective by breaking down complex topics into pieces that are easy to understand. In other words, putting things <strong> to scale</strong>."
	byline="By Andres Larios "
	src=""
	alt="A flat design of a California Scrub Jay with a camera around its neck, and a logo that says To Scale."
/>

<!-- Hero with video -->
<!-- <Hero
	hed="This is a placeholder headline"
	dek="Welcome to this demo"
	byline="By This Person and That Person"
	src="assets/demo/test.mp4"
	alt="Flourescent jellyfish moving around"
/> -->
<style>
	.hero-container {
		margin-top: 60px; /* Adjust this value to match the height of your header */
	}
</style>
