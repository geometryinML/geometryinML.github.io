---
title: "Divergence-Free Shape Correspondence by Deformation"
collection: publications
permalink: /publication/2019-sgp-divergence-free-shape-correspondence-by-deformation
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2019-07-01
venue: 'Symposium on Geometry Processing (SGP)'
paperurl: 'http://zorah.github.io/files/pdfs/eisenberger2019divfree.pdf'
authors: 'Marvin Eisenberger, <b>Zorah Lähner</b>, Daniel Cremers'
teaser: /previews/eisenberger2019divfree.png
arxiv: 'https://arxiv.org/abs/1806.10417'
categories: [correspondence]
bibtex: true
---

{{ page.authors }}

<img class="col two teaser" src="../images/previews/eisenberger2019divfree.png" alt="Teaser Image" title="teaser" />

## Abstract

> We propose the first algorithm for non-rigid 2D-to-3D shape matching, where the input is a 2D query shape as well as a 3D target shape and the output is a continuous matching curve represented as a closed contour on the 3D shape. We cast the problem as finding the shortest circular path on the product 3-manifold of the two shapes. We prove that the optimal matching can be computed in polynomial time with a (worst-case) complexity of O(mn^2 log(n)), where m and n denote the number of vertices on the 2D and the 3D shape respectively. Quantitative evaluation confirms that the method provides excellent results for sketch-based deformable 3D shape retrieval.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex

    @InProceedings{eisenberger2019divfree,
        author       = {Marvin Eisenberger and Zorah L\"ahner and Daniel Cremers},
        title        = {Divergence-Free Shape Correspondence by Deformation},
        booktitle    = {Symposium on Geometry Processing {(SGP)}},
        year         = {2019},
    }
