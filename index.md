---
layout: home
---
<div class="user-details">
<p id="about" style="text-align: justify;"> &nbsp;&nbsp;&nbsp;&nbsp;
<h2> About </h2>
<p style="text-align: justify;">Welcome! I am a theoretical physics researcher. I study particle physics, cosmology, and particle astro-physics. Besides physics, I am also intersted in music and all kinds of outdoor sports. </p>
	
<div class="user-details2">
<p id="research" style="text-align: justify;"> &nbsp;&nbsp;&nbsp;&nbsp;
<h2> Research  </h2>
<p style="text-align: justify;"> My research is to study the early universe with the help of Quantum Field Theory, high energy particle physics and gravitational wave physics. This mainly involves to answer why the universe contains more matter than antimatter; the production mechanism of dark matter, their nature and how detect them; cosmological phase transitions; topological defects such as cosmic string, domain wall; and the cosmological background of stochastic gravitational waves. In addition, I'm also interested in the primordial black hole as a dark matter candidate and the primordial cosmic inflation.</p> 
	
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
