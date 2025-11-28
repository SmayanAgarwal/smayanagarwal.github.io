---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

I am working on my fourth year thesis under the guidance of [Professor Aalok Thakkar](aalok-thakkar.github.io) as a part of the Weighted Automata Group. The topic of my thesis is 'Probability Distributions over Strings'. We are focused on studying such probability distributions through the lens of finite state machines. As a part of this group, I have had one publication at the DATAMOD symposium, a satellite event of Software Engineering and Formal Methods (SEFM) 2025. 


<iframe src="{{ '/files/_DataMod_2025__Revised.pdf' | relative_url }}" width="100%" height="600px" style="border:none;">
  <p>Unable to display PDF. 
    <a href="{{ '/files/_DataMod_2025__Revised.pdf' | relative_url }}" download>Download it here</a>.
  </p>
</iframe>


<!-- 
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

<!-- New style rendering if publication categories are defined -->
<!-- {% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %} -->



