---
title: "Unsupervised Dense Shape Correspondence using Heat Kernels"
collection: publications
permalink: /publication/2020-3dv-unsupervised-dense-shape-correspondence-using-heat-kernels
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2020-10-01
venue: 'Conference on 3D Vision (3DV)'
paperurl: 'http://zorah.github.io/files/pdfs/aygun2020heatkernel.pdf'
authors: 'Mehmet Aygün, <b>Zorah Lähner</b>, Daniel Cremers'
teaser: /previews/aygun2020heatkernel.png
arxiv: 'https://arxiv.org/abs/2010.12682'
categories: [correspondence, geometricDL]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/aygun2020heatkernel.png" alt="Teaser Image" title="teaser" />

## Abstract

> In this work, we propose an unsupervised method for learning dense correspondences between shapes using a recent deep functional map framework. Instead of depending on ground-truth correspondences or the computationally expensive geodesic distances, we use heat kernels. These can be computed quickly during training as the supervisor signal. Moreover, we propose a curriculum learning strategy using different heat diffusion times which provide different levels of difficulty during optimization without any sampling mechanism or hard example mining. We present the results of our method on different benchmarks which have various challenges like partiality, topological noise and different connectivity.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}


## Bibtex

    @InProceedings{aygun2020heatkernel,
        author 	= {Mehmet Ayg\"un and Zorah L\"ahner and Daniel Cremers},
        title 	= {Unsupervised Dense Shape Correspondence using Heat Kernels},
        booktitle    	= {Conference on 3D Vision {(3DV)}},
        year 		= {2020},
    }
