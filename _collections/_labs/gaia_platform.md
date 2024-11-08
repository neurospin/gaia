---
layout: page_team
title: Platform
cat: gaia
subcat: cell
headline: Support for scientific research and massive image processing
teasing: Our goal is to meet the specific needs of NeuroSpin researchers for software development and analysis of heterogeneous brain data (neuroimaging, omics, clinical and behavioural data) used in the context of research conducted in clinical neuroscience, population imaging or cognitive neuroscience research.
leader: Antoine Grigis
icon: platform.jpg
added: 2020
permalink: cells/gaia-platform.html
---

<!-- Banner -->
<section id="banner">
<div class="content">
  <header><p>{{ page.title }}</p></header>
  <p>
​   {{page.teasing}}
  </p>
  <p>
    <b> Leader: </b>
    <script>mail2("{{page.leader | replace: " ", "." | downcase}}", "cea", 3, "", "{{page.leader}}")</script>
  </p>
</div>
<span class="image object">
  <img src="{{site.url}}{{site.baseurl}}/images/labs/{{page.icon}}" alt="" />
</span>
</section>

<!-- Content -->
<br>
The mission of the cell is to meet the various needs of research teams in support of software development and brain data analysis, including:

<span style='font-size:20px;'>&#8594;</span>The development of ad hoc software tools to meet the specific needs of research teams based in or using the NeuroSpin platform. <br>
<span style='font-size:20px;'>&#8594;</span>The development of brain data analysis pipelines based on standard tools used by the scientific community. <br>
<span style='font-size:20px;'>&#8594;</span>The development of webservices that allow remote control of the developed pipelines and the access to the data produced. <br>
<span style='font-size:20px;'>&#8594;</span>The deployment of these tools on the high performance computing resources of NeuroSpin (CPU and GPU clusters) and of the CEA Très Grand Centre de Calcul (via the EBRAINS/FENIX infrastructure). <br>
<span style='font-size:20px;'>&#8594;</span>The availability of a catalogue listing all the tools produced by the cell. More specifically, within the framework of various research projects conducted by the BAOBAB unit, the cell analyses population imaging data from small, medium and large monocentric, multicentric, national, European or international cohorts acquired on healthy subjects (IMAGEN, HCP, UK BioBank, …) or patients (R-link, EUAIMS, HBN, …) in order to develop population stratification approaches and thus be able to identify the predisposition of each individual to develop brain pathologies. This work is carried out in close collaboration with the UMS CATI.
