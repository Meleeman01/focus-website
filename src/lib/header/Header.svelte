<script>
	import { page } from '$app/stores';
	//import logo from './svelte-logo.svg';
</script>

<header>
	

	<nav>
		
		<ul>
			<li class:active={$page.url.pathname === '/'}><a sveltekit:prefetch href="/">Home
			<span>•</span></a></li>
			<li class:active={$page.url.pathname === '/schedule'}>
				<a sveltekit:prefetch href="/schedule">Schedule <span>•</span></a>
			</li>
			<li class:active={$page.url.pathname === '/venue'}>
				<a sveltekit:prefetch href="/venue">Venue <span>•</span> </a>
			
			</li>
			
			<li >
				<a href="#-">Tickets</a>
			</li>
		</ul>
		
	</nav>

	
</header>

<style>
	header {
		display: flex;
		justify-content: center;
	}

	span {
		color: var(--heading-color);
		margin-left: 1rem;
	}
	nav {
		display: flex;
		justify-content: center;
		--background: rgba(255, 255, 255, 0.7);
	}


	ul {
		position: relative;
		padding: 0;
		margin: 0;
		height: 3em;
		display: flex;
		justify-content: center;
		align-items: center;
		flex-wrap: wrap;
		list-style: none;
		background: var(--background);
		background-size: contain;
	}

	li {
		position: relative;
		height: 100%;
	}

	li.active::before {
		--size: 6px;
		content: '';
		width: 0;
		height: 0;
	}

	nav a {
		display: flex;
		height: 100%;
		align-items: center;
		padding: 0 1em;
		color: var(--heading-color);
		font-weight: 700;
		font-size: 0.8rem;
		text-transform: uppercase;
		letter-spacing: 0.1em;
		text-decoration: none;
		transition: color 0.2s linear;

	}

	a:hover {
		color: var(--accent-color);
	}
</style>
