---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<style>
  .archive h3 { margin-top: 2.2em; margin-bottom: 0.2em; }
  .archive h3 + p { margin-bottom: 0.2em; }
  .archive p { margin-bottom: 0.3em; }
</style>

I did my fourth year thesis with [Professor Aalok Thakkar](https://aalok-thakkar.github.io). Most of my research till now has been a part of that project. Broadly speaking, my research was on weighted automata and formal language theory. We focused on understanding representations of probability distributions over strings. It also won the **Best Thesis** award.


### Probability Distributions over Strings
*Undergraduate Thesis, Ashoka University (2026)*

My [formal thesis defence presentation]({{ '/files/Smayan Agarwal Thesis Presentation.key' | relative_url }}) was intended for an audience that does not specialise in theoretical CS.

To get a more complete idea of what my thesis is, please have a look at [this]({{ '/files/Smayan Agarwal Thesis Report.pdf' | relative_url }}).

For people unfamiliar with weighted automata, these are the [slides]({{ '/files/Weighted Automata Lecture.pptx' | relative_url }}) for a lecture I gave on them. For a more authoritative resource, consider these [lecture notes]({{ '/files/Weighted Automata Lecture Notes.pdf' | relative_url }}).

### From Transformers to Weighted Automata: Towards the Verification of Large Language Models
*DATAMOD 2025, a satellite event of Software Engineering and Formal Methods (SEFM) 2025*

This [paper]({{ '/files/DataMod_2025__Revised.pdf' | relative_url }}) was a result of auxiliary research that I conducted during my thesis.


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



