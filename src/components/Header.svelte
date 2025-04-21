<script>
	import Logo from "$components/icons/Logo.svelte";
	import Logotext from "$components/icons/Logotext.svelte";
</script>

<header class="header">
	<div class="branding-container">
		<div class="logo-container">
			<Logo />
		</div>
		<div class="logotext-container">
			<Logotext />
		</div>
	</div>
	<nav>
		<!-- Add navigation links here -->
		<a href="/">Home</a>
		<a href="/about">About Me</a>
		<a href="/stories">Published Stories</a>
		<a href="/projects">Projects</a>
		<a href="/contact">Contact</a>
	</nav>
</header>

<style>
	.header {
		width: 100%;
		height: 150px;
		display: flex;
		align-items: center;
		justify-content: space-between;
		background-color: #cec6c4;
		padding: 0 1rem;
		position: fixed;
		top: 0;
		left: 0;
		box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
		z-index: 1000;
		border: black solid 5px;
	}
	.branding-container {
		display: flex;
		align-items: center;
	}
	.logo-container {
		display: flex;
		align-items: center;
		width: 130px; /* Adjust width as needed */
		height: 130px; /* Adjust height as needed */
		border-radius: 50%;
		background-color: black;
		border: 3px solid white;
		box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
	}

	.logo-container .svg-icon {
		width: 60px; /* Adjust size as needed */
		height: 100px;
	}

	.logotext-container {
		display: flex;
		align-items: center;
		margin-left: 10px;
	}

	.logotext-container .svg-icon {
		width: 100px; /* Adjust size as needed */
		height: auto;
	}
	nav a {
		color: white;
		text-decoration: none;
		margin-left: 1rem;
		margin-right: 1rem;
		font-size: 1rem;
		padding-left: 5px;
		padding-right: 5px;
		border-left: 2px solid white;
		border-right: 2px solid white;
		transition: border-color 0.3s ease;
		stroke: black;
		stroke-width: 2px black;
	}
	nav a:hover {
		color: black;
		text-decoration: underline, overline;
	}
</style>
