---
title: "Machado Lab - Publications"
layout: gridlay
excerpt: "Machado Lab: Publications"
sitemap: false
permalink: /publications/
---

# Selected Publications

**A more complete list of publications can be found on [Google Scholar](https://scholar.google.com/citations?user=55-MRK4AAAAJ&hl=en).**


{% for publi in site.data.publist %}
{% if publi.highlight == 1 %}

<div class="row">

<div class="col-sm-6 col-md-12">
 <div class="well clearfix" style="height: auto">
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img thumbnail" width="20%" style="float: left" />
  <pubtit>{{ publi.title }}</pubtit>
  <p><em>{{ publi.authors }}</em></p>
  <p> {{ publi.ref }}</p>
  <p> {{ publi.news }}</p>
  <p> {{ publi.link }}</p>
 </div>
</div>
</div>

{% endif %}
{% endfor %}


## Other Publications

{% for publi in site.data.publist %}
{% if publi.highlight == 0 %}

<div class="row">

<div class="col-sm-6 col-md-12">
 <div class="well clearfix" style="height: auto">
  <pubtit>{{ publi.title }}</pubtit>
  <p><em>{{ publi.authors }}</em></p>
  <p> {{ publi.ref }}</p>
 </div>
</div>
</div>

{% endif %}
{% endfor %}


<p> &nbsp; </p>


