<script lang="ts">
	export let name: string;
</script>

<main>
	<header class="intro">
		<div class="container">
			<nav class="navbar navigation-wrapper navbar-dark navbar-expand-lg">
				<div id="logo-wrapper">
					<a href="/">
						<img src="/assets/images/a0dc119.svg" alt="Trilon - Next-level Application Consulting from NestJS and Angular Universal Core team members" class="logo">
					</a>
				</div>
				<button type="button" aria-label="Toggle navigation" aria-controls="nav_collapse" aria-expanded="false" class="navbar-toggler">
					<span class="navbar-toggler-icon"></span>
				</button>
				<div id="nav_collapse" class="navbar-collapse collapse" style="display:none">
					<ul class="navbar-nav ml-auto">
						<li class="nav-item selected">
							<a target="_self" href="/" class="nav-link">Home</a>
						</li> 
						<li class="nav-item">
							<a target="_self" href="/" class="nav-link">Services</a>
						</li> 
						<li class="nav-item">
							<a target="_self" href="/" class="nav-link">Team</a>
						</li> 
						<li class="nav-item">
							<a target="_self" href="/" class="nav-link">Careers</a>
						</li> 
						<li class="nav-item highlight">
							<a target="_self" href="/" class="nav-link">Blog</a>
						</li> 
						<li class="nav-item">
							<a target="_self" href="#" class="nav-link">Contact Us</a>
						</li>
					</ul> 
					<div class="social-wrapper">
						<a href="https://twitter.com/trilon_io" target="blank" class="social-link">
							<svg aria-hidden="true" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
								<path fill="#fff" d="M459.37 151.716c.325 4.548.325 9.097.325 13.645 0 138.72-105.583 298.558-298.558 298.558-59.452 0-114.68-17.219-161.137-47.106 8.447.974 16.568 1.299 25.34 1.299 49.055 0 94.213-16.568 130.274-44.832-46.132-.975-84.792-31.188-98.112-72.772 6.498.974 12.995 1.624 19.818 1.624 9.421 0 18.843-1.3 27.614-3.573-48.081-9.747-84.143-51.98-84.143-102.985v-1.299c13.969 7.797 30.214 12.67 47.431 13.319-28.264-18.843-46.781-51.005-46.781-87.391 0-19.492 5.197-37.36 14.294-52.954 51.655 63.675 129.3 105.258 216.365 109.807-1.624-7.797-2.599-15.918-2.599-24.04 0-57.828 46.782-104.934 104.934-104.934 30.213 0 57.502 12.67 76.67 33.137 23.715-4.548 46.456-13.32 66.599-25.34-7.798 24.366-24.366 44.833-46.132 57.827 21.117-2.273 41.584-8.122 60.426-16.243-14.292 20.791-32.161 39.308-52.628 54.253z"></path>
							</svg>
						</a> 
						<a href="https://github.com/trilonio" target="blank" class="social-link">
							<svg aria-hidden="true" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 496 512" data-fa-i2svg="">
								<path fill="#fff" d="M165.9 397.4c0 2-2.3 3.6-5.2 3.6-3.3.3-5.6-1.3-5.6-3.6 0-2 2.3-3.6 5.2-3.6 3-.3 5.6 1.3 5.6 3.6zm-31.1-4.5c-.7 2 1.3 4.3 4.3 4.9 2.6 1 5.6 0 6.2-2s-1.3-4.3-4.3-5.2c-2.6-.7-5.5.3-6.2 2.3zm44.2-1.7c-2.9.7-4.9 2.6-4.6 4.9.3 2 2.9 3.3 5.9 2.6 2.9-.7 4.9-2.6 4.6-4.6-.3-1.9-3-3.2-5.9-2.9zM244.8 8C106.1 8 0 113.3 0 252c0 110.9 69.8 205.8 169.5 239.2 12.8 2.3 17.3-5.6 17.3-12.1 0-6.2-.3-40.4-.3-61.4 0 0-70 15-84.7-29.8 0 0-11.4-29.1-27.8-36.6 0 0-22.9-15.7 1.6-15.4 0 0 24.9 2 38.6 25.8 21.9 38.6 58.6 27.5 72.9 20.9 2.3-16 8.8-27.1 16-33.7-55.9-6.2-112.3-14.3-112.3-110.5 0-27.5 7.6-41.3 23.6-58.9-2.6-6.5-11.1-33.3 2.6-67.9 20.9-6.5 69 27 69 27 20-5.6 41.5-8.5 62.8-8.5s42.8 2.9 62.8 8.5c0 0 48.1-33.6 69-27 13.7 34.7 5.2 61.4 2.6 67.9 16 17.7 25.8 31.5 25.8 58.9 0 96.5-58.9 104.2-114.8 110.5 9.2 7.9 17 22.9 17 46.4 0 33.7-.3 75.4-.3 83.6 0 6.5 4.6 14.4 17.3 12.1C428.2 457.8 496 362.9 496 252 496 113.3 383.5 8 244.8 8zM97.2 352.9c-1.3 1-1 3.3.7 5.2 1.6 1.6 3.9 2.3 5.2 1 1.3-1 1-3.3-.7-5.2-1.6-1.6-3.9-2.3-5.2-1zm-10.8-8.1c-.7 1.3.3 2.9 2.3 3.9 1.6 1 3.6.7 4.3-.7.7-1.3-.3-2.9-2.3-3.9-2-.6-3.6-.3-4.3.7zm32.4 35.6c-1.6 1.3-1 4.3 1.3 6.2 2.3 2.3 5.2 2.6 6.5 1 1.3-1.3.7-4.3-1.3-6.2-2.2-2.3-5.2-2.6-6.5-1zm-11.4-14.7c-1.6 1-1.6 3.6 0 5.9 1.6 2.3 4.3 3.3 5.6 2.3 1.6-1.3 1.6-3.9 0-6.2-1.4-2.3-4-3.3-5.6-2z"></path>
							</svg>
						</a>
					</div>
				</div>
			</nav>

			<h1 class="trilon-title">
				We are Trilon
				<span class="trilon-pink">.</span>
			</h1>

			<h2 class="trilon-slogan">
				Open Source Fanatics &amp;
				<br>Key Contributors
			</h2>

			<br>
			<a href="#" class="btn btn-primary">Check our Services</a>
			<a href="#" class="btn btn-link">More about Trilon</a>
			<br>
			<div class="scroll-down-wrapper">
				<img src="data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjUxMnB0IiB2aWV3Qm94PSItMTA1IDAgNTEyIDUxMi4wMDAwMiIgd2lkdGg9IjUxMnB0IiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPjxwYXRoIGZpbGw9IiNmZmYiIGQ9Im0xNTAuNjAxNTYyIDBjLTgzLjA0Mjk2OCAwLTE1MC42MDE1NjIgNjcuNTU4NTk0LTE1MC42MDE1NjIgMTUwLjYwMTU2MnYyMTAuNzk2ODc2YzAgODMuMDQyOTY4IDY3LjU1ODU5NCAxNTAuNjAxNTYyIDE1MC42MDE1NjIgMTUwLjYwMTU2MiA4My4wNDI5NjkgMCAxNTAuNjAxNTYzLTY3LjU1ODU5NCAxNTAuNjAxNTYzLTE1MC42MDE1NjJ2LTIxMC43OTY4NzZjMC04My4wNDI5NjgtNjcuNTU4NTk0LTE1MC42MDE1NjItMTUwLjYwMTU2My0xNTAuNjAxNTYyem0xMTkuODgyODEzIDM2MS4zOTg0MzhjMCA2Ni4xMDE1NjItNTMuNzgxMjUgMTE5Ljg4MjgxMi0xMTkuODgyODEzIDExOS44ODI4MTItNjYuMTAxNTYyIDAtMTE5Ljg4MjgxMi01My43ODEyNS0xMTkuODgyODEyLTExOS44ODI4MTJ2LTIxMC43OTY4NzZjMC02Ni4xMDE1NjIgNTMuNzgxMjUtMTE5Ljg4MjgxMiAxMTkuODgyODEyLTExOS44ODI4MTIgNjYuMTAxNTYzIDAgMTE5Ljg4MjgxMyA1My43ODEyNSAxMTkuODgyODEzIDExOS44ODI4MTJ6bTAgMCIvPjxwYXRoIGZpbGw9IiNmZmYiIGQ9Im0xNTAuNjA1NDY5IDEwMS44NTE1NjJjLTguNDg0Mzc1IDAtMTUuMzU5Mzc1IDYuODc1LTE1LjM1OTM3NSAxNS4zNTkzNzZ2NzAuNjk1MzEyYzAgOC40ODA0NjkgNi44NzUgMTUuMzU5Mzc1IDE1LjM1OTM3NSAxNS4zNTkzNzUgOC40ODA0NjkgMCAxNS4zNTkzNzUtNi44Nzg5MDYgMTUuMzU5Mzc1LTE1LjM1OTM3NXYtNzAuNjk1MzEyYzAtOC40ODQzNzYtNi44NzUtMTUuMzU5Mzc2LTE1LjM1OTM3NS0xNS4zNTkzNzZ6bTAgMCIvPjwvc3ZnPg==" class="icon-mouse"> 
				<img src="/assets/images/a824d0a.svg" class="arrow-long">
			</div>
		</div>
	</header>

	<div class="wave-wrapper">
		<section class="dark-bg wwd-wrapper margin-top-rwd">
			<div id="services">
				<div class="container">
					<h2 class="heading">
        				What we do
						<!----> <span class="trilon-pink heading-dot">.</span>
					</h2> 
					<p class="subheading">
        				At Trilon, our goal is to help elevate teams - giving them the push they need to
        				truly succeed in today's ever-changing tech world.
						<br> 
						<br>
					</p> 
					<div class="services row">
						<div class="service col-sm-6 col-lg-3">
							<img src="/assets/images/359c459.svg" alt="Trilon - Consulting" class="wwd-icon"> 
							<h2>
            					Consulting
								<span class="trilon-pink">.</span>
							</h2> 
							<p class="gray">
            					Let us help take your Application to the next level - planning the next big steps,
            					reviewing architecture, and brainstorming with the team to ensure you
            					achieve your most ambitious goals!
							  </p>
						</div> 
						<div class="service col-sm-6 col-lg-3">
							<img src="/assets/images/89c7c2d.svg" alt="Trilon - Development and Team Augmentation" class="wwd-icon"> 
							<h2>
            					Development
								<span class="trilon-pink">.</span>
							</h2> 
							<p class="gray">
            					Trilon can become part of your development process, making sure that
            					you're building enterprise-grade, scalable applications with best-practices in mind,
            					all while getting things done better and faster!
							  </p>
						</div> 
						<div class="service col-sm-6 col-lg-3">
							<img src="/assets/images/d526502.svg" alt="Trilon - Workshops on NestJS, Node, and other modern JavaScript topics" class="wwd-icon"> 
							<h2>
            					Workshops
								<span class="trilon-pink">.</span>
							</h2> 
							<p class="gray">
            					Have a Trilon team member come to YOU! Get your team up to speed with guided
            					workshops on a huge variety of topics. Modern NodeJS (or NestJS) development, JavaScript frameworks,
            					Reactive Programming, or anything in between! We've got you covered.
							</p>
						</div> 
						<div class="service col-sm-6 col-lg-3">
							<img src="/assets/images/3a4325c.svg" alt="Trilon - Open-source contributors" class="wwd-icon"> 
							<h2>
            					Open-source
								<span class="trilon-pink">.</span>
							</h2> 
							<p class="gray">
            					We love open-source because we love giving back to the community!
            					We help maintain &amp; contribute to some of the largest open-source projects, and hope to always
            					share our knowledge with the world!
							</p>
						</div>
					</div> 
					<a href="/services" class="btn btn-primary mt-4">
        				Explore more
						<svg enable-background="new 0 0 32 32" height="32px" version="1.1" viewBox="0 0 32 32" width="32px" xml:space="preserve" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" class="arrow-icon">
							<path clip-rule="evenodd" d="M32,16.009c0-0.267-0.11-0.522-0.293-0.714  l-9.899-9.999c-0.391-0.395-1.024-0.394-1.414,0c-0.391,0.394-0.391,1.034,0,1.428l8.193,8.275H1c-0.552,0-1,0.452-1,1.01  s0.448,1.01,1,1.01h27.586l-8.192,8.275c-0.391,0.394-0.39,1.034,0,1.428c0.391,0.394,1.024,0.394,1.414,0l9.899-9.999  C31.894,16.534,31.997,16.274,32,16.009z" fill="#fff" fill-rule="evenodd" id="Arrow_Forward"></path>
						</svg>
					</a>
				</div>
			</div>
		</section> 
		<div id="team" class="our-team-wrapper dark-bg">
			<div class="container">
				<h2 class="heading">
      				Our team
				  <span class="trilon-pink heading-dot">.</span>
				</h2> 
				<p class="subheading">
					We've worked with small start-ups, to Fortune 500 companies, leading them all to success.
				</p> 
				<div class="team-wrapper-row row">
					<div class="trilon-member col-xs-12 col-sm-6 col-md-6 col-lg-4 offset-lg-2">
						<div class="member-thumbnail cursor-pointer">
							<img src="/assets/images/845fe45.png" alt="Kamil Mysliwiec | Trilon">
						</div> <div class="member-title">
							<h5 class="twitter-handle trilon-pink">
								<a href="https://twitter.com/kammysliwiec" target="_blank" rel="noopener" class="trilon-pink">@kammysliwiec</a>
							</h5> <!----> 
							<h2 class="founder cursor-pointer">Kamil Mysliwiec</h2>
          					Co-Founder
						</div> 
						<p class="gray member-description">
							<a href="https://nestjs.com/" rel="noopener" target="_blank">NestJS</a> 
							Framework Creator
							<br> 
							Google Developer Expert
							<br> International Speaker
							<br> Educator
							<br> Cat lover
						</p> 
						<br> 
						<br> 
						<div class="read-more">
							<span class="gray">more</span> 
							<svg enable-background="new 0 0 32 32" height="32px" version="1.1" viewBox="0 0 32 32" width="32px" xml:space="preserve" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" class="arrow-icon">
								<path clip-rule="evenodd" d="M32,16.009c0-0.267-0.11-0.522-0.293-0.714  l-9.899-9.999c-0.391-0.395-1.024-0.394-1.414,0c-0.391,0.394-0.391,1.034,0,1.428l8.193,8.275H1c-0.552,0-1,0.452-1,1.01  s0.448,1.01,1,1.01h27.586l-8.192,8.275c-0.391,0.394-0.39,1.034,0,1.428c0.391,0.394,1.024,0.394,1.414,0l9.899-9.999  C31.894,16.534,31.997,16.274,32,16.009z" fill="#fff" fill-rule="evenodd" id="Arrow_Forward"></path>
							</svg>
						</div>
					</div>
					<div class="trilon-member col-xs-12 col-sm-6 col-md-6 col-lg-4">
						<div class="member-thumbnail cursor-pointer">
							<img src="/assets/images/9a3eb99.png" alt="Mark Pieszak | Trilon">
						</div> 
						<div class="member-title">
							<h5 class="twitter-handle trilon-pink">
								<a href="https://twitter.com/markpieszak" target="_blank" rel="noopener" class="trilon-pink">@markpieszak</a>
							</h5> <!----> 
							<h2 class="founder cursor-pointer">Mark Pieszak</h2>
          					Co-Founder
						</div> 
						<p class="gray member-description">
							<a href="https://github.com/angular/universal#universal-team" rel="noopener" target="_blank">Angular Universal</a> 
							team
							<br> 
							Creator of ASP.NET Vue &amp; ASP.NET Angular
							<br> 
							International Speaker
							<br> 
							Educator
						</p> 
						<br> 
						<br> 
						<div class="read-more">
							<span class="gray">more</span> 
							<svg enable-background="new 0 0 32 32" height="32px" version="1.1" viewBox="0 0 32 32" width="32px" xml:space="preserve" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" class="arrow-icon">
								<path clip-rule="evenodd" d="M32,16.009c0-0.267-0.11-0.522-0.293-0.714  l-9.899-9.999c-0.391-0.395-1.024-0.394-1.414,0c-0.391,0.394-0.391,1.034,0,1.428l8.193,8.275H1c-0.552,0-1,0.452-1,1.01  s0.448,1.01,1,1.01h27.586l-8.192,8.275c-0.391,0.394-0.39,1.034,0,1.428c0.391,0.394,1.024,0.394,1.414,0l9.899-9.999  C31.894,16.534,31.997,16.274,32,16.009z" fill="#fff" fill-rule="evenodd" id="Arrow_Forward"></path>
							</svg>
						</div>
					</div>
				</div> 
				<div id="member-profile" class="member-wrapper member-details collapsed">
					<div class="gradient-wrapper">
						<span class="close-icon">
							<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" id="Capa_1" x="0px" y="0px" viewBox="0 0 212.982 212.982" xml:space="preserve" style="enable-background:new 0 0 212.982 212.982">
								<g id="Close">
									<path d="M131.804,106.491l75.936-75.936c6.99-6.99,6.99-18.323,0-25.312   c-6.99-6.99-18.322-6.99-25.312,0l-75.937,75.937L30.554,5.242c-6.99-6.99-18.322-6.99-25.312,0c-6.989,6.99-6.989,18.323,0,25.312   l75.937,75.936L5.242,182.427c-6.989,6.99-6.989,18.323,0,25.312c6.99,6.99,18.322,6.99,25.312,0l75.937-75.937l75.937,75.937   c6.989,6.99,18.322,6.99,25.312,0c6.99-6.99,6.99-18.322,0-25.312L131.804,106.491z" fill="#FFFFFF" style="fill-rule:evenodd;clip-rule:evenodd"></path>
								</g>
							</svg>
						</span> 
						<div class="row">
							<div class="d-sm-none d-md-block col-xs-12 col-md-3 col-lg-4 member-photo">
								<img alt="undefined | Trilon Consulting">
							</div> 
							<div class="col-sm-12 col-md-9 col-lg-8 member-info">
								<!----> <!----> <h3></h3> 
								<div class="member-socials">
									<!----> <!----> 
								</div> 
								<p></p> 
								<div class="videos-wrapper row align-items-center"> </div>
							</div>
						</div>
					</div>
				</div>
			</div> 
			<div class="view-team-wrapper" data-v-3d13041a="">
				<a href="/" class="btn btn-primary mt-5" data-v-3d13041a="">Get to know us</a>
			</div> 
			<img src="/assets/images/309c77f.png" class="wave-lower-large">
		</div>
	</div>

	<div class="container our-talks-wrapper">
		<div class="container">
			<h2 class="text-uppercase mega-font">
				We've visited
				<span class="trilon-gradient">15</span>
				countries with our lectures
			</h2> 
			<button aria-label="Watch some of them" class="btn btn-primary">Watch some of them
				<svg enable-background="new 0 0 32 32" height="32px" version="1.1" viewBox="0 0 32 32" width="32px" xml:space="preserve" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" class="arrow-icon arrow-down">
					<path clip-rule="evenodd" d="M32,16.009c0-0.267-0.11-0.522-0.293-0.714  l-9.899-9.999c-0.391-0.395-1.024-0.394-1.414,0c-0.391,0.394-0.391,1.034,0,1.428l8.193,8.275H1c-0.552,0-1,0.452-1,1.01  s0.448,1.01,1,1.01h27.586l-8.192,8.275c-0.391,0.394-0.39,1.034,0,1.428c0.391,0.394,1.024,0.394,1.414,0l9.899-9.999  C31.894,16.534,31.997,16.274,32,16.009z" fill="#fff" fill-rule="evenodd" id="Arrow_Forward"></path>
				</svg>
			</button>
		</div> 
		<div>
			<br> 
			<div id="trilon-conference-talks" class="video-wrapper">
				<div>
					<div>
						<h6 class="gray">Kamil Mysliwiec | JsKongress 2019 - Munich, Germany</h6> 
						<h3 class="talk-title">Taming reactive Node.js: Stream-oriented architecture with Nest</h3> 
						<div class="video-player"> 
							<iframe src="https://www.youtube.com/embed/c8hvW14VdkY?controls=1&amp;modestbranding=1&amp;rel=0&amp;start=0" width="100%" height="413" title="Taming reactive Node.js: Stream-oriented architecture with Nest" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>
						</div>
					</div>
				</div>
				<div>
					<!---->
				</div>
				<div><!----></div>
				<div><!----></div> 
				<div class="video-selection-wrapper text-right">
					<svg enable-background="new 0 0 32 32" height="32px" version="1.1" viewBox="0 0 32 32" width="32px" xml:space="preserve" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" class="arrow-icon arrow arrow-left">
						<path clip-rule="evenodd" d="M32,16.009c0-0.267-0.11-0.522-0.293-0.714  l-9.899-9.999c-0.391-0.395-1.024-0.394-1.414,0c-0.391,0.394-0.391,1.034,0,1.428l8.193,8.275H1c-0.552,0-1,0.452-1,1.01  s0.448,1.01,1,1.01h27.586l-8.192,8.275c-0.391,0.394-0.39,1.034,0,1.428c0.391,0.394,1.024,0.394,1.414,0l9.899-9.999  C31.894,16.534,31.997,16.274,32,16.009z" fill="#fff" fill-rule="evenodd" id="Arrow_Forward"></path>
					</svg> 
					<div class="circle selected"></div>
					<div class="circle"></div>
					<div class="circle"></div>
					<div class="circle"></div> 
					<svg enable-background="new 0 0 32 32" height="32px" version="1.1" viewBox="0 0 32 32" width="32px" xml:space="preserve" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" class="arrow-icon arrow">
						<path clip-rule="evenodd" d="M32,16.009c0-0.267-0.11-0.522-0.293-0.714  l-9.899-9.999c-0.391-0.395-1.024-0.394-1.414,0c-0.391,0.394-0.391,1.034,0,1.428l8.193,8.275H1c-0.552,0-1,0.452-1,1.01  s0.448,1.01,1,1.01h27.586l-8.192,8.275c-0.391,0.394-0.39,1.034,0,1.428c0.391,0.394,1.024,0.394,1.414,0l9.899-9.999  C31.894,16.534,31.997,16.274,32,16.009z" fill="#fff" fill-rule="evenodd" id="Arrow_Forward"></path>
					</svg>
				</div>
			</div>
		</div>
	</div>

	<div class="www-wrapper">
		<div class="container">
			<h2 class="heading">
				Who we're working with
				<span class="trilon-pink heading-dot">.</span>
			</h2> 
			<p class="subheading">
				We've worked with some of the largest enterprise companies and globally used
				open source projects. Now we're ready to help your project become a huge success.
			</p> 
			<div class="row testimonials-wrapper justify-content-md-center">
				<div class="gradient-wrapper">
					<div class="testimonial">
						<div><!----></div>
						<div><!----></div>
						<div>
							<div>
								<div class="author-wrapper">
									<div class="avatar">
										<img src="/assets/images/25a04b8.jpg" alt="Zackary Chapple">
									</div> 
									<div class="author-info">
										<h6 class="author-name">Zackary Chapple</h6> 
										<h5 class="job-position">Principal Architect @ CareerBuilder</h5>
									</div>
								</div> 
								<p class="testimonial-text">
									<strong>Trilon</strong> has helped level-up our teams skills and enterprise best-practices from front-end to back-end development and surrounding ecosystems. Their expertise helped us not only finish products on-time, but helped us create sustainable and reliable software.
								</p>
							</div>
						</div>
					</div>
				</div> 
				<div class="selection-wrapper text-right">
					<svg enable-background="new 0 0 32 32" height="32px" version="1.1" viewBox="0 0 32 32" width="32px" xml:space="preserve" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" class="arrow-icon arrow arrow-left">
						<path clip-rule="evenodd" d="M32,16.009c0-0.267-0.11-0.522-0.293-0.714  l-9.899-9.999c-0.391-0.395-1.024-0.394-1.414,0c-0.391,0.394-0.391,1.034,0,1.428l8.193,8.275H1c-0.552,0-1,0.452-1,1.01  s0.448,1.01,1,1.01h27.586l-8.192,8.275c-0.391,0.394-0.39,1.034,0,1.428c0.391,0.394,1.024,0.394,1.414,0l9.899-9.999  C31.894,16.534,31.997,16.274,32,16.009z" fill="#fff" fill-rule="evenodd" id="Arrow_Forward"></path>
					</svg> 
					<div class="circle"></div>
					<div class="circle"></div>
					<div class="circle selected"></div> 
					<svg enable-background="new 0 0 32 32" height="32px" version="1.1" viewBox="0 0 32 32" width="32px" xml:space="preserve" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" class="arrow-icon arrow">
						<path clip-rule="evenodd" d="M32,16.009c0-0.267-0.11-0.522-0.293-0.714  l-9.899-9.999c-0.391-0.395-1.024-0.394-1.414,0c-0.391,0.394-0.391,1.034,0,1.428l8.193,8.275H1c-0.552,0-1,0.452-1,1.01  s0.448,1.01,1,1.01h27.586l-8.192,8.275c-0.391,0.394-0.39,1.034,0,1.428c0.391,0.394,1.024,0.394,1.414,0l9.899-9.999  C31.894,16.534,31.997,16.274,32,16.009z" fill="#fff" fill-rule="evenodd" id="Arrow_Forward"></path>
					</svg>
				</div>
			</div>
		</div>
	</div>

	<div id="contact-us" class="contactus-wrapper">
		<div class="container">
			<h2 class="heading">
				Write us a message
				<span class="trilon-pink heading-dot">.</span>
			</h2> 
			<p class="subheading">Let's talk about how Trilon can help your next project get to the next level.</p> 
			<form id="contact-form">
				<div class="contact-us-form row">
					<div class="height-control col-sm-12 col-md-4">
						<div class="row"><input placeholder="First name" class="form-control" type="text" style="background-image: url(&quot;data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAABHklEQVQ4EaVTO26DQBD1ohQWaS2lg9JybZ+AK7hNwx2oIoVf4UPQ0Lj1FdKktevIpel8AKNUkDcWMxpgSaIEaTVv3sx7uztiTdu2s/98DywOw3Dued4Who/M2aIx5lZV1aEsy0+qiwHELyi+Ytl0PQ69SxAxkWIA4RMRTdNsKE59juMcuZd6xIAFeZ6fGCdJ8kY4y7KAuTRNGd7jyEBXsdOPE3a0QGPsniOnnYMO67LgSQN9T41F2QGrQRRFCwyzoIF2qyBuKKbcOgPXdVeY9rMWgNsjf9ccYesJhk3f5dYT1HX9gR0LLQR30TnjkUEcx2uIuS4RnI+aj6sJR0AM8AaumPaM/rRehyWhXqbFAA9kh3/8/NvHxAYGAsZ/il8IalkCLBfNVAAAAABJRU5ErkJggg==&quot;); background-repeat: no-repeat; background-attachment: scroll; background-size: 16px 18px; background-position: 98% 50%;"></div> 
						<div class="row"><input type="email" placeholder="E-mail address" class="form-control"></div> 
						<div class="row"><input type="phone" placeholder="Phone number" class="form-control"></div>
					</div> 
					<div class="text-control height-control col-sm-12 col-xs-12 col-md-8">
						<textarea type="text" placeholder="Your Message" class="form-control"></textarea>
					</div>
				</div> 
				<div class="contact-submit-wrapper contact-us-form text-right">
					<div class="text-right">
						<a href="mailto:hello@trilon.io?subject=Trilon%20Consulting&amp;body=%0D%0A%0D%0A**************************%0D%0A%0D%0AName: %0D%0APhone: %0D%0AEmail:" class="btn btn-primary">
			  				Send message
							  <svg enable-background="new 0 0 32 32" height="32px" version="1.1" viewBox="0 0 32 32" width="32px" xml:space="preserve" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" class="arrow-icon">
								<path clip-rule="evenodd" d="M32,16.009c0-0.267-0.11-0.522-0.293-0.714  l-9.899-9.999c-0.391-0.395-1.024-0.394-1.414,0c-0.391,0.394-0.391,1.034,0,1.428l8.193,8.275H1c-0.552,0-1,0.452-1,1.01  s0.448,1.01,1,1.01h27.586l-8.192,8.275c-0.391,0.394-0.39,1.034,0,1.428c0.391,0.394,1.024,0.394,1.414,0l9.899-9.999  C31.894,16.534,31.997,16.274,32,16.009z" fill="#fff" fill-rule="evenodd" id="Arrow_Forward"></path>
							</svg>
						</a>
					</div>
				</div>
			</form> 
			<div class="other-contact-wrapper">
				<h3>Rather send us an email? Write to:</h3> 
				<a href="mailto:hello@trilon.io" class="contact-email">
					<strong>hello</strong>@trilon.io
				</a>
			</div>
		</div>
	</div>
</main>

<style>
	
	@media (min-width: 1500px) {
		.intro {
			max-width: none;
    		background-position-y: -10rem;
		}
	}

	.intro {
    	background: url(/assets/images/fa08324.png) no-repeat top;
    	background-size: cover;
    	min-height: 600px;
	}

	@media (min-width: 1200px) {
		.container {
    		max-width: 1440px;
		}
	}

	.container {
		text-align: center;
	}

	.navigation-wrapper {
    	padding-top: 2rem;
	}

	.navigation-wrapper #logo-wrapper {
    	font-size: 1.2rem;
    	font-weight: 800;
    	text-transform: uppercase;
    	float: left;
	}

	#logo-wrapper, .navbar-toggler-icon {
    	position: relative;
    	z-index: 2;
	}

	.navigation-wrapper .nav-item:first-of-type {
    	margin-left: 0;
	}

	.navigation-wrapper .nav-item {
    	margin-left: 2.4rem;
    	font-weight: 500;
	}

	.social-link {
    	margin: 0 .75rem;
	}

	.social-link svg {
    	width: 18px;
    	height: 18px;
	}

	svg {
	    overflow: hidden;
	}

	img, svg {
	    vertical-align: middle;
	}

	.container .trilon-title {
    	display: block;
    	font-weight: 500;
    	font-size: 6rem;
    	letter-spacing: 3px;
    	padding: 3rem 0 2rem;
    	margin-top: 2rem;
	}

	.container .trilon-slogan {
    	padding-bottom: 5rem;
    	line-height: 2.8rem;
    	font-weight: 400;
	}

	.scroll-down-wrapper {
    	position: relative;
	}

	@media (min-width: 992px) {
		.scroll-down-wrapper {
		    top: 0;
		}
	}

	.scroll-down-wrapper .icon-mouse {
    	width: 28px;
    	top: 4rem;
    	-webkit-animation: moveTop 2s infinite forwards;
    	animation: moveTop 2s infinite forwards;
	}

	.scroll-down-wrapper .arrow-long, .scroll-down-wrapper .icon-mouse {
    	position: absolute;
    	left: 50%;
    	-webkit-transform: translateX(-50%);
    	transform: translateX(-50%);
	}

	.scroll-down-wrapper .arrow-long {
    	top: 6.8rem;
	}

	.wave-wrapper {
    	padding: 15rem 0;
    	background: url(/assets/images/309c77f.png) no-repeat top;
    	background-size: contain;
    	min-height: 2150px;
	}

	@media (min-width: 1520px) {
		.margin-top-rwd {
		    margin-top: 1rem;
		}
	}

	.wwd-wrapper {
    	padding-bottom: 10rem;
	}

	.dark-bg {
    	background: #050710;
	}

	article, aside, figcaption, figure, footer, header, hgroup, main, nav, section {
    	display: block;
	}

	h1, h2.heading {
    	font-size: 3rem;
	}

	.heading {
    	font-weight: 500;
	}

	.heading-dot {
    	margin-left: -.5rem;
	}

	.subheading {
    	max-width: 750px;
    	margin: 0 auto;
	}

	.wwd-wrapper .services {
    	padding: 5rem 0 6.5rem;
	}

	.wwd-wrapper .wwd-icon {
    	max-width: 60px;
	}

	@media (min-width: 1520px) {
		.our-team-wrapper {
		    margin-bottom: 1rem;
		}
	}

	.our-team-wrapper .team-wrapper-row {
    	margin-top: 5.5rem;
	}

	.our-team-wrapper .team-wrapper-row .trilon-member {
    	margin-bottom: 3rem;
	}

	.our-team-wrapper .trilon-member .member-thumbnail {
	    margin: 0 auto;
	    width: 145px;
	    -webkit-transition: all .15s ease-in;
	    transition: all .15s ease-in;
	    border-radius: 3px;
	    overflow: hidden;
	    -webkit-filter: grayscale(100%);
	    filter: grayscale(100%);
	}

	.our-team-wrapper .member-title {
	    min-height: 150px;
	}

	.our-team-wrapper .twitter-handle {
	    margin-top: 2rem;
	    font-size: 1.1rem;
	}

	.our-team-wrapper .founder {
	    font-size: 1.5rem;
	    font-weight: 700;
	}

	.our-team-wrapper .member-description {
	    max-width: 250px;
	    min-height: 150px;
	    margin: 0 auto;
	}

	.gray {
	    color: hsla(0,0%,100%,.709804);
	}

	.our-team-wrapper .read-more * {
	    -webkit-transition: all .15s ease-in-out;
	    transition: all .15s ease-in-out;
	}

	.view-team-wrapper[data-v-3d13041a] {
	    padding: 2rem 0;
	    text-align: center;
	}

	@media (min-width: 1501px) {
		.our-team-wrapper .wave-lower-large {
		    display: block;
		}
	}

	.our-team-wrapper .wave-lower-large {
	    display: none;
	    position: absolute;
	    left: 0;
	    right: 0;
	    width: 100%;
	    -webkit-transform: rotate(180deg);
	    transform: rotate(180deg);
	}

	.cursor-pointer {
		color: #fff;
		cursor: pointer;
	}

	.our-team-wrapper .trilon-member .member-thumbnail img {
    	width: 100%;
    	-webkit-transition: all .15s ease-in;
    	transition: all .15s ease-in;
	}

	.our-team-wrapper .read-more svg {
	    -webkit-transform: rotate(90deg);
	    transform: rotate(90deg);
	    width: 20px;
	}

	a:hover {
	    color: #7f19e9;
	    text-decoration: none;
	}

	.our-team-wrapper .trilon-member:hover .read-more {
	    cursor: pointer;
	}

	.our-team-wrapper .read-more * {
	    -webkit-transition: all .15s ease-in-out;
	    transition: all .15s ease-in-out;
	}

	.our-team-wrapper .trilon-member:hover .read-more {
	    cursor: pointer;
	}

	.our-team-wrapper .collapsed {
	    -webkit-transition: all .35s ease-in-out;
	    transition: all .35s ease-in-out;
	    -webkit-transform: translateY(-1.5rem);
	    transform: translateY(-1.5rem);
	    max-height: 0;
	    overflow: hidden;
	    opacity: 0;
	}

	.our-team-wrapper .member-details {
	    -webkit-transition: all .35s ease-in-out,opacity .35s ease .4s,-webkit-transform .35s ease .4s;
	    transition: all .35s ease-in-out,opacity .35s ease .4s,-webkit-transform .35s ease .4s;
	    transition: all .35s ease-in-out,opacity .35s ease .4s,transform .35s ease .4s;
	    transition: all .35s ease-in-out,opacity .35s ease .4s,transform .35s ease .4s,-webkit-transform .35s ease .4s;
	}

	.gradient-wrapper {
		padding: 5px 20px;
		border-radius: 5px;
    	background: #e91e63;
    	background: -webkit-linear-gradient(135deg,#e91e63,#7f19e9);
	}

	.member-wrapper .close-icon {
	    position: absolute;
	    width: 18px;
	    height: 18px;
	    z-index: 10;
	    right: 40px;
	    top: 35px;
	}

	.member-photo {
	    padding: 0;
	    overflow: hidden;
	}

	.member-photo img {
	    min-width: 100%;
	    min-height: 100%;
	    max-width: none;
	    left: 50%;
	    -webkit-transform: translateX(-50%);
	    transform: translateX(-50%);
	    position: absolute;
	}

	.member-info {
	    padding: 1.5rem 2rem 0;
	}

	.member-info .trilon-pink {
	    font-weight: 500;
	}

	.member-socials {
	    margin: .5rem 0;
	}

	.member-socials a {
	    color: #fff;
	    margin: 0 .2rem;
	}

	.member-info p {
	    font-size: .95rem;
	    line-height: 1.6rem;
	    color: #edeef0;
	}

	.gradient-wrapper .row {
	    background: #070a19;
	}

	.member-wrapper .videos-wrapper {
	    display: -webkit-box;
	    display: flex;
	    -webkit-box-pack: justify;
	    justify-content: space-between;
	    margin-top: 2.5rem;
	}

	.member-wrapper .videos-wrapper .video {
	    position: relative;
	}

	.view-team-wrapper[data-v-3d13041a] {
    	padding: 2rem 0;
    	text-align: center;
	}

	@media (min-width: 1501px) {
		.our-team-wrapper .wave-lower-large {
		    display: block;
		}
	}

	.our-team-wrapper .wave-lower-large {
    	position: absolute;
    	left: 0;
    	right: 0;
    	width: 100%;
    	-webkit-transform: rotate(180deg);
		transform: rotate(180deg);
	}

	.our-talks-wrapper {
	    background: url(/assets/images/3693ddc.png) no-repeat top;
	    min-height: 600px;
	    padding-top: 5rem;
	}
	.our-talks-wrapper .video-wrapper {
	    padding: 10rem 0 6rem;
	    text-align: left;
	    max-width: 800px;
	    margin: 0 auto;
	}

	.our-talks-wrapper .video-wrapper .talk-title {
	    min-height: 60px;
	}

	.our-talks-wrapper .video-wrapper .video-player {
	    margin: 3rem 0 0;
	    min-height: 425px;
	    background: url(/assets/images/a0dc119.svg) no-repeat 50%;
	    background-size: contain;
	}

	.our-talks-wrapper .video-wrapper .video-selection-wrapper {
	    margin: 3rem 1.5rem 0;
	}

	.our-talks-wrapper .video-wrapper .video-selection-wrapper * {
	    vertical-align: middle;
	    cursor: pointer;
	}

	.our-talks-wrapper .video-wrapper .video-selection-wrapper .circle.selected {
	    cursor: auto;
	    background: #e91e63;
	}

	.our-talks-wrapper .video-wrapper .video-selection-wrapper .circle {
	    background: #302641;
	    width: 20px;
	    height: 20px;
	    border-radius: 50%;
	    display: inline-block;
	    margin: 0 .25rem;
	}

	.arrow-icon {
	    width: 1.5rem;
	    margin-left: 1rem;
	}

	.www-wrapper .heading {
	    padding-bottom: 1rem;
	}

	@media (min-width: 1440px) {
		.www-wrapper {
		    background-size: contain;
		}
	}

	.www-wrapper {
	    background: url(/assets/images/664988f.png) no-repeat bottom;
	    margin-top: 3rem;
	}

	.testimonials-wrapper {
	    padding-top: 5rem;
	    max-width: 1000px;
	    margin: 0 auto;
	}

	.testimonials-wrapper .gradient-wrapper {
	    padding: 5px;
	}

	.gradient-wrapper {
	    border-radius: 5px;
	    background: #e91e63;
	    background: -webkit-linear-gradient(135deg,#e91e63,#7f19e9);
	}

	.testimonials-wrapper .gradient-wrapper>div {
	    padding: 80px 110px;
	    text-align: left;
	}

	.gradient-wrapper>div {
	    background: #070a19;
	}

	.selection-wrapper {
	    margin: 3rem auto 0;
	}

	.arrow-left {
	    -webkit-transform: rotate(-180deg);
	    transform: rotate(-180deg);
	    margin-right: 1rem;
	    margin-left: 0;
	}

	.selection-wrapper * {
	    vertical-align: middle;
	    cursor: pointer;
	}

	.selection-wrapper .circle {
	    background: #302641;
	    width: 20px;
	    height: 20px;
	    border-radius: 50%;
	    display: inline-block;
	    margin: 0 .25rem;
	}

	.contactus-wrapper {
	    background: url(/assets/images/8d60929.png) no-repeat bottom,#050710;
	    padding: 9rem 0 20rem;
	}

	.contactus-wrapper .contact-us-form {
	    max-width: 968px;
	    margin: 2rem auto 0;
	}

	.contactus-wrapper .contact-us-form .height-control input, .contactus-wrapper .contact-us-form .height-control textarea {
	    margin-top: 1.5rem;
	}

	.form-control {
	    background: #1e0e40;
	    color: hsla(0,0%,100%,.709804);
	    border: 0;
	    padding: 1.8rem 1.5rem;
	    box-shadow: none!important;
	    font-size: .9rem;
		width: 100%;
		display: block;
		height: calc(1.5em + .75rem + 2px);
		font-weight: 400;
		line-height: 1.5;
		border-radius: .25rem;
		transition: border-color .15s ease-in-out,box-shadow .15s ease-in-out;
	}

	@media (min-width: 768px) {
		.contactus-wrapper .contact-us-form .text-control {
    	padding: 0 0 0 1.5rem;
	}
	}

	.contactus-wrapper .contact-us-form textarea {
	    height: 90%;
	}

	.contactus-wrapper .contact-submit-wrapper {
	    padding-top: 3rem;
	}

	.contactus-wrapper .contact-us-form {
	    max-width: 968px;
	    margin: 2rem auto 0;
	}

	.contactus-wrapper .other-contact-wrapper {
	    margin: 5rem 0 0;
	}

	.contactus-wrapper .other-contact-wrapper .contact-email {
	    color: #fff;
	    font-size: 3rem;
	}

	.mega-font {
	    font-weight: 900;
	    font-size: 5.5rem;
	    width: 60%;
	    margin: 0 auto;
	    padding: 0 0 3rem;
	}

	.trilon-gradient {
	    color: #e91e63;
	    background: -webkit-linear-gradient(bottom left,#e91e63,#7f19e9);
	    -webkit-background-clip: text;
	    background-clip: text;
		-webkit-text-fill-color: transparent;
	}

	.arrow-down {
	    -webkit-transform: rotate(90deg);
	    transform: rotate(90deg);
	}

	.testimonials-wrapper .avatar {
	    width: 50px;
	    height: 50px;
	    border-radius: 50%;
	    overflow: hidden;
	}

	.testimonials-wrapper .author-info, .testimonials-wrapper .avatar {
	    display: inline-block;
	    vertical-align: middle;
	}

	.testimonials-wrapper .author-info {
	    text-align: left;
	    padding-left: 1em;
	}

	.testimonials-wrapper .author-name {
	    margin-bottom: 4px;
	}

	.testimonials-wrapper .job-position {
	    color: #e91e63;
	    font-size: 16px;
	    font-weight: 600;
	    margin: 0;
	}

	.testimonials-wrapper .testimonial-text {
	    margin: 2.5em 0 0;
	    font-weight: 400;
	    font-size: 16px;
	    line-height: 28px;
	}

	.testimonials-wrapper .testimonial-text strong {
	    color: #e91e63;
	}

	img {
		max-width: 100%;
	}

</style>