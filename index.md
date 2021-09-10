---
layout: home
---
<div class="user-details">
<h2> About me </h2>
<p style="text-align: justify;"> Welcome!  I am a physicist in China.  I study theoretical cosmology, elementary particle physics, and particle astro-physics.  My research in these fields seeks to address some of the most exciting, persistent, and challenging problems in physics today. </p>
	
	
<div class="user-details2">	
<h2> Reseach interests </h2>
<p style="text-align: justify;"> My work addresses open questions in the study of theoretical cosmology by using the tools of elementary particle physics and particle astrophysics.</p>
<ul>
    <li>Why the universe contains more matter than antimatter and how we can test the physics of “baryogenesis” using high-energy particle collider experiments or astrophysical observations;</li>
    <li>Why most of the particles in the universe are made of an ephemeral “dark matter,” how did it form, and what is its nature;</li>
    <li>What can we learn about the universe from measurements of gravitational waves.</li>
</ul>

<div class="permlinks">
<h2>Recent articles</h2>
<dl>
	{% for post in site.posts limit:3 %}
	<dt><code>{{ post.date | date_to_string }} </code><i class="fas fa-angle-double-right" aria-hidden="true"></i><a href="{{ post.url }}">{{ post.title }}</a> &nbsp;{% include status-indicator.html status=post.status%}
	{% if post.description %}
 <dd style="text-align: justify">{{ post.description | markdownify }}
    </dd>
	{% endif %}
	{% endfor %}
	<p>... <a href="/blog">More</a> </p>
</dl>
</div >
	
	
	
<div class="analytics"  style="border: solid lightgrey; border-radius: 5px;">
	<h3> Analytics </h3>
	{% include clustrmap.html style="js" %}
	<p> <small> If you are not seeing a map, please disable Ad block </small></p>
</div>	
