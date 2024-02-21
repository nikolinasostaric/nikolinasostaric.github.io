---
layout: page
title: RNA distribution clustering 
description: A collaboration with Marianne Bauer
img: assets/img/Clusters2.png
importance: 2
category: ongoing
related_publications: 
---

T cells play an important role in our immune system. To be able to effectively clear tumors and viruses, T cells have to switch from resting to an activated state. This switch includes substantial remodeling of T cell’s transcriptome and proteome.  

We previously used experimental data to build distribution profiles of RNAs among different ribosome-bound states, which are a proxy for RNA translation. By comparing distributions between resting and activated state of T cells, we can learn what happens to translation of certain RNA species when cells become activated. 

In this project, we want to learn which types of distributions RNAs follow and how they change upon T cell activation. To this aim, we will cluster RNA distributions based on their shape. We will initially rely on the intuition that for each biologically meaningful cluster of RNA distributions, the clusters should be Gaussian distributed for each condition of T-cell activation. We will then cluster RNA translation profiles with a constraint of Gaussian distributions in each cluster. For comparison, we can use an information-theoretic clustering and k-means, and compare also to RNA clusters in the clustering found so far using the Pearson coefficient. In parallel, we will investigate what distributions fit best the currently found clusters, and variations over conditions.

Practically, this project involves you familiarizing yourself with data-analysis methods, including ones where we can make analytical progress. You will learn how to interpret your clusterings both through the data, as well as through a mathematical analysis of the clustering, that should be able help predict when different clustering methods yield different results.

<small>Cover figure: Initial hierarchical clustering. </small>
