<script lang="ts">
	// No imports needed for pure brutalist design
</script>

<svelte:head>
	<title>PORTAL SALE - MAXIMUM VALUE</title>
	<meta name="description" content="Brutalist portal sales with maximum value and minimum BS" />
</svelte:head>

<!-- BRUTALIST PORTAL SALES -->
<div class="brutalist-container">
	<!-- BANNER/NAVBAR -->
	<div id="banner" class="banner-sticky">
		<h1>20% OFF DUE TO NEW YEAR</h1>
	</div>
	
	<!-- HEADER SECTION -->
	<header class="hero-section">
		<div class="hero-content">
			<h1 class="hero-title">
				BUY THIS<br>
				<span class="hero-subtitle">PORTAL</span><br>
				NOW
			</h1>
			<p class="hero-description">
				MAXIMUM VALUE. MINIMUM PRICE.<br>
				BUY FAST. BUY NOW. BUY MORE.
			</p>
			<div class="hero-cta">
				<a href="#pricing" class="cta-primary">BUY NOW</a>
				<a href="#features" class="cta-secondary">SEE FEATURES</a>
			</div>
		</div>
	</header>

	<!-- FEATURES SECTION -->
	<section id="features" class="features-section">
		<div class="section-header">
			<h2 class="section-title">FEATURES</h2>
			<p class="section-subtitle">WHAT YOU GET</p>
		</div>
		
		<div class="features-grid">
			<div class="feature-card">
				<div class="feature-number">01</div>
				<h3 class="feature-title">INSTANT ACCESS</h3>
				<p class="feature-description">DOWNLOAD IMMEDIATELY. NO WAITING. NO BULLSHIT.<br>INSTANT GRATIFICATION. INSTANT RESULTS.</p>
				<div class="feature-meta">
					<span class="feature-speed">0 SECONDS</span>
					<span class="feature-type">INSTANT</span>
				</div>
			</div>

			<div class="feature-card">
				<div class="feature-number">02</div>
				<h3 class="feature-title">STABILITY</h3>
				<p class="feature-description">USE AS MUCH AS YOU WANT. NO RESTRICTIONS . THIS SHIT DOESN'T BREAKS <br>UNLIMITED POWER. UNLIMITED VALUE.</p>
				<div class="feature-meta">
					<span class="feature-speed">FOREVER</span>
					<span class="feature-type">STABLE</span>
				</div>
			</div>

			<div class="feature-card">
				<div class="feature-number">03</div>
				<h3 class="feature-title">PREMIUM SUPPORT</h3>
				<p class="feature-description">24/7 SUPPORT. REAL PEOPLE. REAL HELP.<br>NO AUTOMATED BULLSHIT. HUMAN SUPPORT.</p>
				<div class="feature-meta">
					<span class="feature-speed">24/7</span>
					<span class="feature-type">HUMAN</span>
				</div>
			</div>

			<div class="feature-card">
				<div class="feature-number">04</div>
				<h3 class="feature-title">MONEY BACK</h3>
				<p class="feature-description">30-DAY GUARANTEE. NO QUESTIONS ASKED.<br>IF YOU DON'T LIKE IT, GET YOUR MONEY BACK.</p>
				<div class="feature-meta">
					<span class="feature-speed">30 DAYS</span>
					<span class="feature-type">GUARANTEED</span>
				</div>
			</div>
		</div>
	</section>

	<!-- PRICING SECTION -->
	<section id="pricing" class="pricing-section">
		<div class="section-header">
			<h2 class="section-title">PRICING</h2>
			<p class="section-subtitle">PAY LESS. GET MORE.</p>
		</div>
		
		<div class="pricing-grid">
			<div class="pricing-card">
				<h3 class="pricing-title">BASIC</h3>
				<div class="pricing-amount">$29</div>
				<p class="pricing-period">ONE TIME</p>
				<ul class="pricing-features">
					<li>BASIC PORTAL ACCESS</li>
					<li>EMAIL SUPPORT</li>
					<li>STANDARD FEATURES</li>
					<li>30-DAY GUARANTEE</li>
				</ul>
				<button class="pricing-cta">CHOOSE BASIC</button>
			</div>

			<div class="pricing-card featured">
				<div class="pricing-badge">BEST VALUE</div>
				<h3 class="pricing-title">STANDARD</h3>
				<div class="pricing-amount"></div>
				<p class="pricing-period">ONE TIME</p>
				<ul class="pricing-features">
					<li>EVERYTHING IN BASIC</li>
					<li>PREMIUM FEATURES</li>
					<li>PRIORITY SUPPORT</li>
				</ul>
				<button class="pricing-cta">CHOOSE PROFESSIONAL</button>
			</div>

			<div class="pricing-card">
				<h3 class="pricing-title">CUSTOM</h3>
				<div class="pricing-amount">AS PER REQUEST </div>
				<p class="pricing-period">ONE TIME</p>
				<ul class="pricing-features">
					<li>EVERYTHING IN PRO</li>
					<li>WHITE LABEL RIGHTS</li>
					<li>CUSTOM BRANDING</li>
					<li>DEDICATED MANAGER</li>
					<li>API ACCESS</li>
				</ul>
				<button class="pricing-cta">CHOOSE ENTERPRISE</button>
			</div>
		</div>
	</section>

	<!-- TESTIMONIALS SECTION -->
	<section class="testimonials-section">
		<div class="section-header">
			<h2 class="section-title">REVIEWS</h2>
			<p class="section-subtitle">REAL CUSTOMERS. REAL MONEY.</p>
		</div>
		
		<div class="testimonials-grid">
			<div class="testimonial-card">
				<div class="testimonial-quote">"OUR SCHOOL HAS SEEN A 20% INCREASE IN STUDENT ENGAGEMENT SINCE WE UPGRADED TO THE THIS PORTAL ."</div>
				<div class="testimonial-author">RAHUL KUMAR</div>
				<div class="testimonial-role">PRINCIPAL</div>
			</div>

			<div class="testimonial-card">
				<div class="testimonial-quote">"FINALLY, A PORTAL THAT ACTUALLY WORKS. NO BULLSHIT. JUST RESULTS."</div>
				<div class="testimonial-author">SARAH DEVI</div>
				<div class="testimonial-role">VC</div>
			</div>

			<div class="testimonial-card">
				<div class="testimonial-quote">"THIS IS A REALLY GOOD PORTAL"</div>
				<div class="testimonial-author">MOHAN KUMAR</div>
				<div class="testimonial-role">PRINCIPAL</div>
			</div>
		</div>
	</section>

	<!-- FINAL CTA SECTION -->
	<section class="final-cta-section">
		<h2 class="final-cta-title">STOP SCROLLING. START BUYING.</h2>
		<p class="final-cta-description">
			THE PRICE GOES UP IN 24 HOURS.<br>
			ACT NOW OR REGRET FOREVER.
		</p>
		<a href="#pricing" class="final-cta-button">SECURE YOUR PORTAL</a>
	</section>

	<!-- FOOTER -->
	<footer class="brutalist-footer">
		<div class="footer-content">
			<div class="footer-section">
				<h3>PORTAL SALE</h3>
				<p>MAXIMUM VALUE. MINIMUM PRICE.</p>
			</div>
			<div class="footer-section">
				<h4>PRODUCT</h4>
				<ul>
					<li><a href="#features">FEATURES</a></li>
					<li><a href="#pricing">PRICING</a></li>
					<li><a href="#support">SUPPORT</a></li>
					<li><a href="#guarantee">GUARANTEE</a></li>
				</ul>
			</div>
			<div class="footer-section">
				<h4>COMPANY</h4>
				<ul>
					<li><a href="/">KMOS</a></li>
					<li><a href="#about">ABOUT</a></li>
					<li><a href="#contact">CONTACT</a></li>
					<li><a href="#refund">REFUND POLICY</a></li>
				</ul>
			</div>
			<div class="footer-section">
				<h4>SECURE</h4>
				<ul>
					<li><a href="#privacy">PRIVACY</a></li>
					<li><a href="#security">SECURITY</a></li>
					<li><a href="#ssl">SSL SECURE</a></li>
				</ul>
			</div>
		</div>
		<div class="footer-bottom">
			<p>© 2024 PORTAL SALE. ALL RIGHTS RESERVED. SECURE PAYMENTS.</p>
		</div>
	</footer>
</div>

<style>
	/* BRUTALIST RESET & BASE STYLES */
	:global(*) {
		margin: 0;
		padding: 0;
		box-sizing: border-box;
	}

	:global(body) {
		font-family: 'Courier New', monospace;
		background: #fff;
		color: #000;
		line-height: 1.4;
		letter-spacing: -0.02em;
	}

	:global(html) {
		scroll-behavior: smooth;
	}

	/* MAIN CONTAINER */
	.brutalist-container {
		width: 100%;
		min-height: 100vh;
		background: #fff;
		color: #000;
	}

	/* BANNER/NAVBAR */
	#banner.banner-sticky {
		position: sticky;
		top: 0;
		left: 0;
		right: 0;
		width: 100%;
		background: #fbbf24;
		color: #000;
		padding: 1rem 2rem;
		text-align: center;
		z-index: 1000;
		border-bottom: 3px solid #000;
		box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.2);
	}

	#banner.banner-sticky h1 {
		margin: 0;
		font-size: clamp(1rem, 2vw, 1.5rem);
		font-weight: 900;
		text-transform: uppercase;
		letter-spacing: 0.05em;
	}

	/* HERO SECTION */
	.hero-section {
		min-height: 100vh;
		display: grid;
		place-items: center;
		padding: 2rem;
		border-bottom: 4px solid #000;
	}

	.hero-content {
		text-align: center;
		max-width: 1200px;
		width: 100%;
	}

	.hero-title {
		font-size: clamp(3rem, 12vw, 8rem);
		font-weight: 900;
		line-height: 0.9;
		text-transform: uppercase;
		letter-spacing: -0.05em;
		margin-bottom: 2rem;
		border: 4px solid #000;
		padding: 3rem 2rem;
		background: #fff;
		box-shadow: 0 8px 16px -4px rgba(255, 255, 255, 0.5);
	}

	.hero-subtitle {
		background: #000;
		color: #fff;
		padding: 0.5rem 1rem;
		display: inline-block;
	}

	.hero-description {
		font-size: clamp(1rem, 3vw, 1.5rem);
		font-weight: 700;
		text-transform: uppercase;
		margin: 3rem 0;
		line-height: 1.3;
	}

	.hero-cta {
		display: flex;
		justify-content: center;
		gap: 2rem;
		flex-wrap: wrap;
	}

	.cta-primary, .cta-secondary {
		display: inline-block;
		padding: 1rem 2rem;
		text-decoration: none;
		text-transform: uppercase;
		font-weight: 900;
		font-size: 1.1rem;
		border: 3px solid #000;
		transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
		background: #000;
		color: #fff;
		box-shadow: 0 4px 6px -1px rgba(255, 255, 255, 0.3);
	}

	.cta-secondary {
		background: transparent;
		color: #000;
		box-shadow: 0 4px 6px -1px rgba(255, 255, 255, 0.3);
	}

	.cta-primary:hover, .cta-secondary:hover {
		background: #000;
		color: #fff;
		transform: translate(-2px, -2px);
		box-shadow: 0 10px 15px -3px rgba(255, 255, 255, 0.4);
	}

	/* SECTION STYLES */
	.section-header {
		text-align: center;
		padding: 4rem 2rem 2rem;
		border-bottom: 3px solid #000;
	}

	.section-title {
		font-size: clamp(2.5rem, 8vw, 5rem);
		font-weight: 900;
		text-transform: uppercase;
		letter-spacing: -0.03em;
		margin-bottom: 1rem;
	}

	.section-subtitle {
		font-size: 1.2rem;
		font-weight: 700;
		text-transform: uppercase;
		letter-spacing: 0.1em;
	}

	/* FEATURES SECTION */
	.features-section {
		padding: 2rem;
		border-bottom: 4px solid #000;
	}

	.features-grid {
		display: grid;
		grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
		gap: 0;
		max-width: 1400px;
		margin: 0 auto;
	}

	.feature-card {
		border: 3px solid #000;
		padding: 2rem;
		background: #fff;
		transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
		box-shadow: 0 4px 6px -1px rgba(255, 255, 255, 0.3);
	}

	.feature-card:hover {
		background: #000;
		color: #fff;
		transform: translate(-4px, -4px);
		box-shadow: 0 10px 15px -3px rgba(255, 255, 255, 0.4);
	}

	.feature-number {
		font-size: 3rem;
		font-weight: 900;
		margin-bottom: 1rem;
	}

	.feature-title {
		font-size: 1.5rem;
		font-weight: 900;
		text-transform: uppercase;
		margin-bottom: 1rem;
		letter-spacing: -0.02em;
	}

	.feature-description {
		font-size: 1rem;
		line-height: 1.4;
		margin-bottom: 2rem;
	}

	.feature-meta {
		display: flex;
		justify-content: space-between;
		font-weight: 700;
		text-transform: uppercase;
		font-size: 0.9rem;
	}

	/* PRICING SECTION */
	.pricing-section {
		padding: 2rem;
		border-bottom: 4px solid #000;
	}

	.pricing-grid {
		display: grid;
		grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
		gap: 0;
		max-width: 1400px;
		margin: 0 auto;
	}

	.pricing-card {
		border: 3px solid #000;
		padding: 3rem 2rem;
		background: #fff;
		text-align: center;
		position: relative;
		transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
		box-shadow: 0 4px 6px -1px rgba(255, 255, 255, 0.3);
	}

	.pricing-card:hover {
		background: #000;
		color: #fff;
		transform: translate(-2px, -2px);
		box-shadow: 0 10px 15px -3px rgba(255, 255, 255, 0.4);
	}

	.pricing-card.featured {
		border-width: 4px;
		background: #000;
		color: #fff;
		box-shadow: 0 8px 10px -3px rgba(255, 255, 255, 0.3);
	}

	.pricing-badge {
		position: absolute;
		top: -1rem;
		left: 50%;
		transform: translateX(-50%);
		background: #fff;
		color: #000;
		padding: 0.5rem 1rem;
		font-size: 0.8rem;
		font-weight: 900;
		text-transform: uppercase;
		border: 2px solid #000;
	}

	.pricing-card.featured .pricing-badge {
		background: #fff;
		color: #000;
		border-color: #fff;
	}

	.pricing-title {
		font-size: 1.8rem;
		font-weight: 900;
		text-transform: uppercase;
		margin-bottom: 2rem;
		letter-spacing: -0.02em;
	}

	.pricing-amount {
		font-size: 4rem;
		font-weight: 900;
		margin-bottom: 0.5rem;
	}

	.pricing-period {
		font-size: 1rem;
		font-weight: 700;
		text-transform: uppercase;
		margin-bottom: 2rem;
	}

	.pricing-features {
		list-style: none;
		margin-bottom: 2rem;
	}

	.pricing-features li {
		padding: 0.5rem 0;
		border-bottom: 1px solid #ccc;
		text-transform: uppercase;
		font-size: 0.9rem;
	}

	.pricing-card.featured .pricing-features li {
		border-bottom-color: #666;
	}

	.pricing-cta {
		display: inline-block;
		padding: 1rem 2rem;
		background: #fff;
		color: #000;
		text-decoration: none;
		text-transform: uppercase;
		font-weight: 900;
		border: 3px solid #fff;
		transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
		cursor: pointer;
		font-family: inherit;
	}

	.pricing-card.featured .pricing-cta {
		background: #fff;
		color: #000;
	}

	.pricing-cta:hover {
		background: #000;
		color: #fff;
		border-color: #000;
	}

	/* TESTIMONIALS SECTION */
	.testimonials-section {
		padding: 2rem;
		border-bottom: 4px solid #000;
	}

	.testimonials-grid {
		display: grid;
		grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
		gap: 0;
		max-width: 1400px;
		margin: 0 auto;
	}

	.testimonial-card {
		border: 3px solid #000;
		padding: 2rem;
		background: #fff;
		transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
		box-shadow: 0 4px 6px -1px rgba(255, 255, 255, 0.3);
	}

	.testimonial-card:hover {
		background: #000;
		color: #fff;
		transform: translate(-2px, -2px);
		box-shadow: 0 10px 15px -3px rgba(255, 255, 255, 0.4);
	}

	.testimonial-quote {
		font-size: 1.1rem;
		line-height: 1.4;
		margin-bottom: 2rem;
		font-style: italic;
	}

	.testimonial-author {
		font-size: 1.2rem;
		font-weight: 900;
		text-transform: uppercase;
		margin-bottom: 0.5rem;
	}

	.testimonial-role {
		font-size: 0.9rem;
		text-transform: uppercase;
		opacity: 0.8;
	}

	/* FINAL CTA SECTION */
	.final-cta-section {
		padding: 4rem 2rem;
		text-align: center;
		border-bottom: 4px solid #000;
	}

	.final-cta-title {
		font-size: clamp(2rem, 6vw, 4rem);
		font-weight: 900;
		text-transform: uppercase;
		margin-bottom: 2rem;
		letter-spacing: -0.03em;
	}

	.final-cta-description {
		font-size: 1.3rem;
		line-height: 1.4;
		margin-bottom: 3rem;
		text-transform: uppercase;
		font-weight: 700;
	}

	.final-cta-button {
		display: inline-block;
		padding: 1.5rem 3rem;
		background: #000;
		color: #fff;
		text-decoration: none;
		text-transform: uppercase;
		font-weight: 900;
		font-size: 1.2rem;
		border: 4px solid #000;
		transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
		box-shadow: 0 4px 6px -1px rgba(255, 255, 255, 0.3);
	}

	.final-cta-button:hover {
		background: #fff;
		color: #000;
		transform: translate(-4px, -4px);
		box-shadow: 0 10px 15px -3px rgba(255, 255, 255, 0.4);
	}

	/* FOOTER */
	.brutalist-footer {
		background: #000;
		color: #fff;
		padding: 3rem 2rem 1rem;
		border-top: 4px solid #000;
	}

	.footer-content {
		display: grid;
		grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
		gap: 2rem;
		max-width: 1400px;
		margin: 0 auto 2rem;
	}

	.footer-section h3, .footer-section h4 {
		font-size: 1.2rem;
		font-weight: 900;
		text-transform: uppercase;
		margin-bottom: 1rem;
		letter-spacing: -0.02em;
	}

	.footer-section ul {
		list-style: none;
	}

	.footer-section li {
		margin-bottom: 0.5rem;
	}

	.footer-section a {
		color: #fff;
		text-decoration: none;
		text-transform: uppercase;
		font-weight: 700;
		font-size: 0.9rem;
		transition: all 0.2s ease;
	}

	.footer-section a:hover {
		text-decoration: underline;
		color: #ccc;
	}

	.footer-bottom {
		border-top: 2px solid #fff;
		padding-top: 1rem;
		text-align: center;
	}

	.footer-bottom p {
		font-size: 0.9rem;
		text-transform: uppercase;
		font-weight: 700;
	}

	/* RESPONSIVE */
	@media (max-width: 768px) {
		.hero-cta {
			flex-direction: column;
			align-items: center;
		}

		.features-grid,
		.pricing-grid,
		.testimonials-grid {
			grid-template-columns: 1fr;
		}

		.feature-card,
		.pricing-card,
		.testimonial-card {
			border-left: none;
			border-right: none;
		}
	}

	/* BRUTALIST HOVER EFFECTS */
	.feature-card:hover .feature-number,
	.pricing-card:hover .pricing-amount,
	.testimonial-card:hover .testimonial-quote {
		transform: scale(1.1);
	}

	/* ACCESSIBILITY */
	@media (prefers-reduced-motion: reduce) {
		:global(*) {
			transition: none !important;
			transform: none !important;
		}
	}
</style>
