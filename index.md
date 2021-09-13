---
layout: home
---
<div class="user-details">
<p id="about" style="text-align: justify;"> &nbsp;&nbsp;&nbsp;&nbsp;
<h2> About </h2>
<p style="text-align: justify;">Welcome!  I am a PhD student in theoretical physics. I study particle physics, cosmology, and particle astro-physics.  My research in these fields seeks to address some of the most exciting, persistent, and challenging problems in physics today. </p>
	
<div class="user-details2">
<p id="research" style="text-align: justify;"> &nbsp;&nbsp;&nbsp;&nbsp;
<h2> Research  </h2>
<p style="text-align: justify;"> My research is employing the Quantum Field Theory, particle physics and gravitational wave physics to study the early universe. This mainly involves cosmological phase transitions, topological defects such as cosmic strings, and the relvent stochastic gravitational waves background. In addition, I also study the production mechanism  of dark matter and their nature. Finally, I'm going to get involved to primordial black hole and inflation.</p>
	
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
