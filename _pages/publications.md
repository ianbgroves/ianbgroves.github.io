---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

---
title: "Of Mitogen and Morphogens: Modelling Sonic Hedgehog in Development"
collection: publications
permalink: /publication/OfMitogenandMorphogen
excerpt: 'This review summarises advances in mathematical and computational model of Sonic Hedgehog, and highlights areas for future work.'
date: 2020-TBC
venue: 'Philosophical Transactions of Royal Society B'
paperurl: 'TBC'
citation: 'Groves, Ian (2020). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
This paper is about the number 1. The number 2 is left for future work.

[Download paper here](TBC)





{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
