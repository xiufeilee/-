---
layout: home
---
<div class="user-details" style="float: left;width:58%;">
<p id="about" style="text-align: justify;"> &nbsp;&nbsp;&nbsp;&nbsp;
	<h1> About  </h1>
<p><font color="#005f6b">Welcome!  I am a physicist in China.  I study theoretical cosmology, elementary particle physics, and particle astro-physics.  My research in these fields seeks to address some of the most exciting, persistent, and challenging problems in physics today.</p>
</p>

<div class="user-details2" style="float: left;width:58%;">
<p id="reseach" style="text-align: justify;"> &nbsp;&nbsp;&nbsp;&nbsp;
	<h1> Reseach </h1>
<p><font color="#005f6b">Welcome!  I am a physicist in China.  I study theoretical cosmology, elementary particle physics, and particle astro-physics.  My research in these fields seeks to address some of the most exciting, persistent, and challenging problems in physics today.</p>
</p>

<div class="user-details2" style="float: left;width:58%;">
<p id="reseach" style="text-align: justify;"> &nbsp;&nbsp;&nbsp;&nbsp;
	<h1> Reseach </h1>
<p><font color="#005f6b">Welcome!  I am a physicist in China.  I study theoretical cosmology, elementary particle physics, and particle astro-physics.  My research in these fields seeks to address some of the most exciting, persistent, and challenging problems in physics today.</p>
</p>
	
	<div class="permlinks">
<p id="articles" style="text-align: left;"> &nbsp;&nbsp;&nbsp;&nbsp;
<h2>Articles</h2>
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
