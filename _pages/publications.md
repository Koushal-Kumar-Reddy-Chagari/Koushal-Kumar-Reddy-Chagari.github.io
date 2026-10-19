---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% if site.author.googlescholar %}
  You can also find my articles on <a href="{{ site.author.googlescholar }}" style="text-decoration: none;">my Google Scholar profile</a>.
{% endif %}

{% assign papers = site.publications | where: "pubtype", "paper" | sort: "date" | reverse %}
{% assign patents = site.publications | where: "pubtype", "patent" | sort: "date" | reverse %}

Papers
======
{% for post in papers %}
<div class="list__item">
  <article class="archive__item">
    <h2 class="archive__item-title"><a href="{{ base_path }}{{ post.url }}" rel="permalink">{{ post.title }}</a></h2>
    <p>{{ post.citation }}{% if post.doi %} DOI: <a href="https://doi.org/{{ post.doi }}">{{ post.doi }}</a>{% endif %}</p>
  </article>
</div>
{% endfor %}

Patents
======
{% for post in patents %}
<div class="list__item">
  <article class="archive__item">
    <h2 class="archive__item-title"><a href="{{ base_path }}{{ post.url }}" rel="permalink">{{ post.title }}</a></h2>
    <p>{{ post.citation }}</p>
  </article>
</div>
{% endfor %}
