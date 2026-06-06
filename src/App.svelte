<script>
  import Links from './Links.svelte'
	import Me from './assets/me.jpeg'
</script>

<section id="center">
    <div id="main">
      <div id="card">
				<div> 
					<h1>kenneth</h1>
				</div>
				<img id="pfp" src={Me} >
        <div id="desc">
					<p> inquisitive explorer </p>
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

