---
title: Curriculum Vitae
layout: page
image: throop_pond.jpg
sect: home
display_img: false
---

[**Download PDF  <i class="far fa-file-pdf"></i>**]({{ site.baseurl}}/assets/Bilgenur_Baloglu_Resume_June2020_github.pdf)

## Education

**B.Sc. Molecular Biology and Genetics**- Istanbul Technical University, *2012*
**Ph.D. Biological Sciences**- National University of Singapore, *2018* 
Thesis topic: Freshwater biomonitoring with Next Generation Sequencing
Advisor: Professor Rudolf Meier

## Publications

{% for pub in site.data.pubs %}
1. {{ pub.authors}} *{{pub.title}}*, {{ pub.journal }} **{{ pub.volume }}** ({{pub.year}}). DOI: {{ pub.doi }}. {% for link in pub.links %} [**\[{{link[0]}}\]**]({{link[1]}})
{% endforinfo{% endfor %}