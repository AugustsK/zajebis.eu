<main>
	<section class="welcome">
		<h1>Zajebis, eu!</h1>
		<h2><a href="https://neinterese.lv/">neinterese.lv</a></h2>
	</section>
</main>

<style>
	main {
		height: 100vh;
		background-color: #FF3CAC;
		background-image: linear-gradient(225deg, #FF3CAC 0%, #784BA0 50%, #2B86C5 100%);
		position: relative;
		padding: 0;
		margin: 0;
		display: flex;
		align-items: center;
		justify-content: center;
	}

	.welcome {
		padding: 1em;
		mix-blend-mode: screen;
	}

	h1, h2 {
		margin: 0;
	}

	a,
	a:visited {
		color: #f4f4f4;
	}

	h1 {
		text-transform: uppercase;
		font-size: 2.25rem;
		font-weight: 600;
		padding: 0.5em 1em;
		color: #1d1e22;
		background-color: #f4f4f4;
		mix-blend-mode: screen;
		border-radius: 0.25em;
		pointer-events: none;
		user-select: none;
	}

	h2 {
		text-transform: uppercase;
		text-align: right;
		color: #f4f4f4;
		font-size: 1rem;
		line-height: 1;
	}

	@media (max-width: 479px) {
		h1,
		h2 {
			text-align: center;
		}
	}
</style>
