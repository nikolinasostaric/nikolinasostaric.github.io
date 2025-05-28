---
layout: page
permalink: /education/
title: education
description: 
nav: true
nav_order: 2
display_categories: [current, past, supervised theses]
---

I'm currently developing an introductory Python course for 1<sup>st</sup> year of <a href="https://www.studyguide.tudelft.nl/a101_displayProgram.do?program_tree_id=29839">Nanobiology program</a>. The course team took part in the Blended Course Design Bootcamp in Dordrecht, June 2024. Course development is further financially supported by TU Delft ESA and Nanobiology program.

For the purposes of the introductory Python course, I made an open interactive textbook <a href="https://books.open.tudelft.nl/home/catalog/book/190">Programming Foundations</a>.

In September 2023, I joined the <a href="https://www.tudelft.nl/en/student/faculties/as-student-portal/organisation/board-of-studies-applied-sciences">Board of Studies</a> Nanobiology. I'm also working on restructuring of the bachelor curriculum in Nanobiology.

In June 2024, I completed University Teaching Qualification (UTQ).

In academic year 2024/2025, I was a member of TU Delft Teaching Academy Panel.

Starting in 2025, I joined Innovation in Delft Engineering Education (IDEE) on the topic of Teaching and Learning in the Age of AI.

In January 2025, I started to work on the project "AI-enhanced programming education for applied scientists" as a TU Delft Education Fellow.


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

<normal> M.Sc. in Nanobiology, TU Delft </normal>

- <small> Lina van Steenis, *Structural complementarity drives selective RNA binding by the SARS-CoV-2 nucleocapsid protein*, 2024-2025 </small>
- <small> Eva Heemskerk, *Spatial localization of cytokine mRNA in CD8+ T cells*, 2024-2025 </small>
- <small> Renske Voerman, *Exploring the protein domain interaction map of yeast polarity in 3D using bioinformatic tools*, 2023-2024 </small>
- <small> Stefan Loonen, *Phosphorylation-induced structural dynamics of SARS-CoV-2 N-protein - Insights from molecular dynamics simulations*, 2023-2024 </small>

<normal> B.Sc. in Nanobiology, TU Delft </normal>

 - <small> Sien Wagenaar, *Engineering a photoreactive ParR substitute for artificial DNA segregation in synthetic cells - insights from molecular dynamics and biophysical characterization*, 2024-2025 </small>
 - <small> Ada Maria Precup, *Defining a protein interaction network - Mapping the interaction partners of Spa2 in yeast*, 2023-2024 </small>
 - <small> Eli Teitler, *Simulating the dynamics of lipid bilayers*, 2023-2024 </small>
 - <small> Owyn Kamerman, *RNA distribution clustering - Unravelling cytotoxic T-cells*, 2023-2024 </small>
 - <small> Jesse Poort, *The viability and potential of Mycoplasma mycoides subsp. capri genes in liposome minimal cell systems*, 2023-2024 </small>

<normal> B.Sc. in Life Science & Technology, TU Delft </normal>

 - <small> Stephany Laclé, *The impact of Arg2579Trp mutation on the homodimer formation of mouse teneurin-3*, 2023-2024 </small>

<normal> M.Sc. in Bioinformatics, KU Leuven </normal>

 - <small> Jaldert François, *Meta-analyses of mutational networks that are affected during evolution experiments using the CAMEL database*, 2020-2021 </small>
 - <small> Michael Shawn Neilson, <i>Expanding the functionalities of CAMEL, the online Compendium of Adaptive Microbial Experiments in the Lab</i>, 2020-2021 </small>
 - <small> Niels Schrauwen, <i>Molecular dynamic modelling of the transport activity of GadC variants that cause increased antibiotic persistence in E. coli</i>, 2020-2021 </small>
 - <small> Wouter Van Assche, <i>Properties of the drug binding pockets in natural variants of human GPCR proteins</i>, 2019-2020 </small>
 - <small> Samuel Nathan Haberman, <i>Uncovering hidden functionalities of mutations: Adding prediction tools to CAMEL - a database of experimental evolution</i>, 2019-2020 </small>
 - <small> Jasper Schelfhout, <i>Effect of acetylation and phosphorylation on protein interactions within the G protein-coupled receptor signalling pathway</i>, 2018-2019 </small>


