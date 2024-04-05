---
layout: page
permalink: /education/
title: education
description: 
nav: true
nav_order: 2
display_categories: [current, past, supervised theses]
---

I'm currently developing an introductory Python course for 1<sup>st</sup> year of <a href="https://www.studyguide.tudelft.nl/a101_displayProgram.do?program_tree_id=29839">Nanobiology program</a>.

In September 2023, I joined the <a href="https://www.tudelft.nl/en/student/faculties/as-student-portal/organisation/board-of-studies-applied-sciences">Board of Studies</a> Nanobiology. I'm also working on restructuring of bachelor's curriculum in Nanobiology.

<div class="projects">
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_projects = site.courses | where: "category", category -%}
  {%- assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include course.html %}
    {%- endfor %}
  </div>
  {% endfor %}

</div>


<normal> M.Sc. in Bioinformatics, KU Leuven </normal>

 - <small> Jaldert François, *Meta-analyses of mutational networks that are affected during evolution experiments using the CAMEL database*, 2020-2021 </small>
 - <small> Michael Shawn Neilson, <i>Expanding the functionalities of CAMEL, the online Compendium of Adaptive Microbial Experiments in the Lab</i>, 2020-2021 </small>
 - <small> Niels Schrauwen, <i>Molecular dynamic modelling of the transport activity of GadC variants that cause increased antibiotic persistence in E. coli</i>, 2020-2021 </small>
 - <small> Wouter Van Assche, <i>Properties of the drug binding pockets in natural variants of human GPCR proteins</i>, 2019-2020 </small>
 - <small> Samuel Nathan Haberman, <i>Uncovering hidden functionalities of mutations: Adding prediction tools to CAMEL - a database of experimental evolution</i>, 2019-2020 </small>
 - <small> Jasper Schelfhout, <i>Effect of acetylation and phosphorylation on protein interactions within the G protein-coupled receptor signalling pathway</i>, 2018-2019 </small>


