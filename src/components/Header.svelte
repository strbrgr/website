<script lang="ts">
	// const nav = [
	// 	{
	// 		name: 'Home',
	// 		link: '/'
	// 	},
	// 	{ name: 'Notes', link: 'https://notes.stierberger.com' }
	// ];
</script>

<header>
	<!-- <nav> -->
	<!-- 	<ul> -->
	<!-- 		{#each nav as entry} -->
	<!-- 			<li> -->
	<!-- 				<a href={entry.link} target="_blank"> -->
	<!-- 					{entry.name} -->
	<!-- 				</a> -->
	<!-- 			</li> -->
	<!-- 		{/each} -->
	<!-- 	</ul> -->
	<!-- </nav> -->
	<h1>hey, I'm Jochen.</h1>
	<p>
		I'm a Software Engineer at nvisia, where I build cutting-edge applications, prioritizing quality
		and performance of the products shipped.
	</p>
</header>

<style>
	header {
		margin-top: 6rem;
	}

	/* ul { */
	/* 	display: flex; */
	/* 	justify-content: flex-end; */
	/* 	gap: 0.75rem; */
	/* 	margin-bottom: 4rem; */
	/* } */
	/**/
	/* li { */
	/* 	list-style-type: none; */
	/* } */
	/**/
	/* a { */
	/* 	color: var(--color-primary-100); */
	/* } */
	/**/
	/* a:hover { */
	/* 	color: var(--color-text); */
	/* } */

	h1 {
		font-size: 1.5rem;
		font-weight: 600;
	}

	h1::before {
		background-color: var(--color-bg);
		content: '';
		position: absolute;
		top: -25px;
		left: 0;
		right: 0;
		width: 100%;
		height: 800px;
		background-position: top;
		background-size: cover;
		background-image: radial-gradient(
			78.57% 78.57% at 55.65% 0.84%,
			#a0aaba 0,
			#4d586a 0,
			rgba(15, 23, 42, 0) 100%
		);
		opacity: 0.3;
		z-index: -1;
		border-radius: inherit;
	}

	p {
		max-width: 40rem;
	}
</style>
