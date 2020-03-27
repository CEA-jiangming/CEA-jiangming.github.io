---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.
{% endif %}

## Articles
{% include base_path %}
<ul>
{% assign item_articles = site.publications | where:"type","articles" %}
{% for item in item_articles reversed %}
    <li>{{ item.citation }}[<a href="{{ item.url }}">More</a>]</li>
{% endfor %}
</ul>

## Proceedings
{% include base_path %}
<ul>
{% assign item_proceedings = site.publications | where:"type","proceedings" %}
{% for item in item_proceedings reversed %}
    <li>{{ item.citation }}[<a href="{{ item.url }}">More</a>]</li>
{% endfor %}
</ul>

## Dissertation
*[Multichannel compressed sensing and its application in radio astronomy]({% link files/thesis.pdf %})* [[Bibtex]]({% link _publications/thesis-Bibtex.html %})