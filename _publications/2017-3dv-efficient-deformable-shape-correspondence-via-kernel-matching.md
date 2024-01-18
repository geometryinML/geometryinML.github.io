---
title: "Efficient Deformable Shape Correspondence via Kernel Matching"
collection: publications
permalink: /publication/2017-3dv-efficient-deformable-shape-correspondence-via-kernel-matching
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2017-10-01
venue: 'International Conference on 3D Vision (3DV)'
paperurl: 'http://zorah.github.io/files/pdfs/vestner17kernel.pdf'
authors: 'Matthias Vestner*, <b>Zorah Lähner</b>*, Amit Boyarski*, Or Litany, Ron Slossberg, Tal Remez, Emanuele Rodolà, Alex M. Bronstein, Michael M. Bronsteins, Ron Kimmel, Daniel Cremers'
teaser: /previews/vestner2017kernel.png
arxiv: 'https://arxiv.org/abs/1707.08991'
code: https://github.com/zorah/KernelMatching
categories: [correspondence]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/vestner2017kernel.png" alt="Teaser Image" title="teaser" />

## Abstract

> We present a method to match three dimensional shapes under non-isometric deformations, topology changes and partiality. We formulate the problem as matching between a set of pair-wise and point-wise descriptors, imposing a continuity prior on the mapping, and propose a projected descent optimization procedure inspired by difference of convex functions (DC) programming.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex

    @InProceedings{vestner2017kernel,
        author = 	{M. Vestner and Z. L\"ahner and A. Boyarski and O. Litany and R. Slossberg and T. Remez and E. Rodol\`a and A. M. Bronstein and M. M. Bronstein and R. Kimmel and D. Cremers},
        title = 	{Efficient Deformable Shape Correspondence via Kernel Matching},
        booktitle=	{International Conference on 3D Vision (3DV)},
        year=	{2017},
        month=	{October},
    }
