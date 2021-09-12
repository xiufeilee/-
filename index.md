---
layout: home
---
<div class="user-details">
<p id="about" style="text-align: justify;"> &nbsp;&nbsp;&nbsp;&nbsp;
<h2> About </h2>
<p style="text-align: justify;">Welcome!  I am a physicist in China.  I study theoretical cosmology, elementary particle physics, and particle astro-physics.  My research in these fields seeks to address some of the most exciting, persistent, and challenging problems in physics today. </p>
	
<div class="user-details2">
<p id="research" style="text-align: justify;"> &nbsp;&nbsp;&nbsp;&nbsp;
<h2> Research  </h2>
<p style="text-align: justify;">My work addresses open questions in the study of theoretical cosmology by using the tools of elementary particle physics and particle astrophysics. I am interested in understanding: why the universe contains more matter than antimatter and how we can test the physics of “baryogenesis” using high-energy particle collider experiments or astrophysical observations; why most of the particles in the universe are made of an ephemeral “dark matter,” how did it form; what is its nature and what can we learn about the universe from measurements of gravitational waves.</p>
![Image](https://xiufeilee.github.io/about/SM.png)	
<div class="user-details3">
<p id="articles" style="text-align: justify;"> &nbsp;&nbsp;&nbsp;&nbsp;
<h2>Articles</h2>
<dl>
	{% for post in site.posts limit:3 %}
	<dt><code>{{ post.date | date_to_string }} </code><i class="fas fa-angle-double-right" aria-hidden="true"></i><a href="{{ post.url }}">{{ post.title }}</a> &nbsp;{% include status-indicator.html status=post.status%}
	{% if post.description %}
 <dd style="text-align: justify">{{ post.description | markdownify }}
    </dd>
	{% endif %}
	{% endfor %}
	<p>... <a href="https://xiufeilee.github.io/blog/">More</a> </p> 

	
	
<div class="analytics">
	<body><a href="https://clustrmaps.com/site/1bjxv" title="Visit tracker"><img src="//www.clustrmaps.com/map_v2.png?d=tv84NyostHCuo1rKof-Rf9piViA_BTs7xK52OQTe24c&cl=ffffff"></a></body> 
</div>


