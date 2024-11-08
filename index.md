---
layout: page_lab
---

{% assign lab = "gaia" %}
{% assign teams_sorted = site.labs | where: "cat", lab | where: "subcat", "team" | sort: "title"  %}
{% assign cells_sorted = site.labs | where: "cat", lab | where: "subcat", "cell" | sort: "title"  %}

<!-- Banner -->
<section id="banner">
<div class="content" style="width: 100%;">
  <p><em>
  Computer vision and machine learning models of brain imaging variability: from population-wide databases to precision models for high-field MRI
  </em></p>
  <p>
  The GAIA laboratory is part of the BAOBAB (<a href="https://www.cea.fr/english" target="_blank">CEA</a>, <a href="https://www.cnrs.fr/en" target="_blank">CNRS</a>, <a href="https://www.universite-paris-saclay.fr/en" target="_blank">Paris-Saclay University</a>) unit in the <a href="https://joliot.cea.fr/drf/joliot/en/Pages/research_entities/NeuroSpin.aspx"  target="_blank">NeuroSpin</a> departement. <a href="https://www.neurospin-wiki.org/pmwiki/Main/DirectionsToNeurospin">Directions to Neurospin</a>.
  </p>
  <!-- <p>
  <b>Teams:</b>
  {% for team in teams_sorted %}
    {% if team.site %}
        <a href="{{team.site}}">{{team.title}}</a>
    {% else %}
        <a href="{{site.url}}{{site.baseurl}}{{team.url}}">{{team.title}}</a>
    {% endif %}
  {% endfor %}
  <br>
  <b>Cells:</b>
  {% for cell in cells_sorted %}
    {% if cell.site %}
        <a href="{{cell.site}}">{{cell.title}}</a>
    {% else %}
        <a href="{{site.url}}{{site.baseurl}}{{cell.url}}">{{cell.title}}</a>
    {% endif %}
  {% endfor %}
   </p> -->
</div>
<div class="">
  <img src="{{site.url}}{{site.baseurl}}/images/banner.png" alt="" style="
    width: 100%;
    height: auto;
    margin-bottom: 2em;
  "/>
</div>
</section>
