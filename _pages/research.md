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

I did my fourth year thesis with [Professor Aalok Thakkar](https://aalok-thakkar.github.io). Most of my research till now has been a part of that project. Broadly speaking, my research was on weighted automata and formal language theory. We focused on understanding representations of probability distributions over strings. This thesis won me the **Best Thesis** award in the department.


### Localising Stochasticity in Weighted Automata
*Foundations of Software Technology and Theoretical Computer Science (FSTTCS) 2026*

This [paper](https://arxiv.org/abs/2602.23805) is the result of my undergraduate thesis, *Probability Distributions over Strings* ([full thesis report]({{ '/files/Smayan Agarwal Thesis Report.pdf' | relative_url }})). My [thesis defence presentation]({{ '/files/Smayan Agarwal Thesis Presentation.key' | relative_url }}) was intended for an audience that does not specialise in theoretical CS.

For people unfamiliar with weighted automata, these are the [slides]({{ '/files/Weighted Automata Lecture.pptx' | relative_url }}) for a lecture I gave on them. For a more authoritative resource, consider these [lecture notes]({{ '/files/Weighted Automata Lecture Notes.pdf' | relative_url }}).

[arXiv link to paper.](https://arxiv.org/abs/2602.23805)

### From Transformers to Weighted Automata: Towards the Verification of Large Language Models
*DATAMOD 2025, a satellite event of Software Engineering and Formal Methods (SEFM) 2025*

This [paper](https://doi.org/10.1007/978-3-032-25552-5_10) was a result of auxiliary research that I conducted during my thesis.

[arXiv link to paper.](https://arxiv.org/abs/2610.04569)


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



