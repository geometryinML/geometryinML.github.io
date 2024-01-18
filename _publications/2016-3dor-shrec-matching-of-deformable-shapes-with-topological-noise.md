---
title: "SHREC'16: Matching of Deformable Shapes with Topological Noise"
collection: publications
permalink: /publication/2016-3dor-shrec-matching-of-deformable-shapes-with-topological-noise
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2016-05-01
venue: 'Eurographics Workshop on 3D Object Retrieval (3DOR)'
paperurl: 'http://zorah.github.io/files/pdfs/laehner2016topkids.pdf'
authors: '<b>Zorah Lähner</b>, Emanuele Rodolà, Michael M. Bronstein, Daniel Cremers, Oliver Burghard, Luca Cosmo, Alexander Dieckmann, Reinhard Klein, Yusuf Sahillioğlu'
teaser: /previews/laehner2016shrec.png
categories: [correspondence, dataset]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/laehner2016shrec.png" alt="Teaser Image" title="teaser" />

## Abstract

> A particularly challenging setting of the shape matching problem arises when the shapes being matched have topological artifacts due to the coalescence of spatially close surface regions – a scenario that frequently occurs when dealing with real data under suboptimal acquisition conditions. This track of the SHREC’16 contest evaluates shape matching algorithms that operate on 3D shapes under synthetically produced topological changes. The task is to produce a pointwise matching (either sparse or dense) between 90 pairs of shapes, representing the same individual in different poses but with different topology. A separate set of 15 shapes with ground-truth correspondence was provided as training data for learning-based techniques and for parameter tuning. Three research groups participated in the contest; this paper presents the track dataset, and describes the different methods and the contest results.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex

    @InProceedings{laehner2016shrec,
        title 		= { {SHREC16}: Matching of Deformable Shapes with Topological Noise},
        author 		= {Zorah L\"ahner and Emanuele Rodol\'a and Michael M. Bronstein and Daniel Cremers and Oliver Burghard and Luca Cosmo and Alexander Dieckmann and Reinhard Klein and Yusuf Sahillioglu},
        booktitle 	= {Proc. of Eurographics Workshop on 3D Object Retrieval {(3DOR)}},
        year 		= {2016},
        month 		= {May},
    }
