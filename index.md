---
layout: home
title: Home
landing-title: Hi, my name is EjongHyuck
description: 
image: 
author: 
nav-menu: 
---

<!-- Banner -->
<section id="banner" class="major">
	<div class="inner">
		<header class="major">
			<h1>{{ page.landing-title }}</h1>
		</header>
		<div class="content">
			<p style="text-transform: uppercase;">{{ site.description }}</p>
			<ul class="actions">
				<li><a href="#one" class="button next scrolly">Get Started</a></li>
			</ul>
		</div>
	</div>
</section>

<!-- Main -->
<div id="main">

<!-- One -->
{% include tiles.html %}

<!-- Two -->
<section id="two">
	<div class="inner">
		<header class="major">
			<h2>Who is EjongHyuck?</h2>
		</header>
		<p>EjongHyuck(a.k.a. Makart) is a game developer currently working at Studio Prism. Using the Unity game engine best, and studying with great interest in Javascript. Also interested in 3D graphics rendering so studying shader hard.</p>
		<ul class="actions">
			<li><a href="about.html" class="button next">More info</a></li>
		</ul>
	</div>
</section>

</div>

