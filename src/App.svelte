<script>
  import Links from './Links.svelte'

	const personJsonLd = {
		'@context': 'https://schema.org',
		'@type': 'Person',
		name: 'Kenneth Yang',
		url: 'https://knthyang.xyz',
		image: 'https://knthyang.xyz/me.jpeg',
		sameAs: [
			'https://github.com/1knth',
			'https://open.spotify.com/user/31q3fbmkgoh52x3k7ku2tvrrmqwq'
		]
	}
</script>

<svelte:head>
	<title>Kenneth Yang | Personal Site</title>
	<meta name="description" content="Kenneth Yang — personal website, projects, music, and links." />
	<meta property="og:title" content="Kenneth Yang | Personal Site" />
	<meta property="og:description" content="Kenneth Yang — personal website, projects, music, and links." />
	<meta property="og:type" content="website" />
	<meta property="og:url" content="https://knthyang.xyz" />
	<meta property="og:image" content="https://knthyang.xyz/me.jpeg" />
	<script type="application/ld+json">{JSON.stringify(personJsonLd)}</script>
</svelte:head>

<section id="center">
    <div id="main">
      <div id="card">
				<div> 
					<h1>Kenneth Yang</h1>
				</div>
				<img id="pfp" src="/me.jpeg" alt="Kenneth Yang" >
        <div id="desc">
					<p>inquisitive explorer</p>
					<div>
						<p> what i'm </p>
						<div id="links">
								<!-- <a href="https://open.spotify.com/user/31q3fbmkgoh52x3k7ku2tvrrmqwq" target="_blank"> listening to </a> -->
								<!-- <a href="https://github.com/1knth" target="_blank"> working on </a> -->
								<Links/>
						</div>
					</div>
        </div>
      </div>
			<p id="inquiries"> (knthyang)gmail.com </p>
    </div>
</section>

