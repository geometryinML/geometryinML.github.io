---
title: "Functional Maps Representation on Product Manifolds"
collection: publications
permalink: /publication/2019-cgf-functional-maps-representation-on-product-manifolds
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2019-12-01
venue: 'Computer Graphics Forum (CGF)'
paperurl: 'http://zorah.github.io/files/pdfs/rodola2019funmaprep.pdf'
authors: 'Emanuele Rodolà, <b>Zorah Lähner</b>, Alex M. Bronstein, Michael M. Bronstein, Justin Solomon'
teaser: /previews/rodola2019funmaprep.png
arxiv: 'https://arxiv.org/abs/1809.10940'
categories: [correspondence]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/rodola2019funmaprep.png" alt="Teaser Image" title="teaser" />

## Abstract

> We consider the tasks of representing, analysing and manipulating maps between shapes. We model maps as densities over the product manifold of the input shapes; these densities can be treated as scalar functions and therefore are manipulable using the language of signal processing on manifolds. Being a manifold itself, the product space endows the set of maps with a geometry of its own, which we exploit to define map operations in the spectral domain; we also derive relationships with other existing representations (soft maps and functional maps). To apply these ideas in practice, we discretize product manifolds and their Laplace–Beltrami operators, and we introduce localized spectral analysis of the product manifold as a novel tool for map processing. Our framework applies to maps defined between and across 2D and 3D shapes without requiring special adjustment, and it can be implemented efficiently with simple operations on sparse matrices.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}


## Bibtex

    @article{rodola2018funmaprep,
        title 		= {Functional Maps Representation on Product Manifolds},
        author 	=  {Rodol\`a, Emanuele and L\"ahner, Zorah and Bronstein, Alex M. and Bronstein, Michael M. and Solomon, Justin},
        journal = {{Computer Graphics Forum (CGF)}},
        volume 	= 38,
        issue = 1,
        year = {2019},
    }
