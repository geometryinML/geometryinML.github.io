---
title: "Smooth Shells: Multi-Scale Shape Registration with Functional Maps"
collection: publications
permalink: /publication/2020-cvpr-smooth-shells-multi-scale-shape-registration-with-functional-maps
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2020-06-01
venue: 'Conference on Computer Vision and Pattern Recognition (CVPR)'
paperurl: 'http://zorah.github.io/files/pdfs/eisenberger2020smoothshells.pdf'
authors: 'Marvin Eisenberger, <b>Zorah Lähner</b>, Daniel Cremers'
teaser: /previews/eisenberger2020smoothshells.png
arxiv: 'https://arxiv.org/abs/1905.12512'
code: https://github.com/marvin-eisenberger/smooth-shells
categories: [correspondence]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/eisenberger2020smoothshells.png" alt="Teaser Image" title="teaser" />

## Abstract

> We propose a novel 3D shape correspondence method based on the iterative alignment of so-called smooth shells. Smooth shells define a series of coarse-to-fine shape approximations designed to work well with multiscale algorithms. The main idea is to first align rough approximations of the geometry and then add more and more details to refine the correspondence. We fuse classical shape registration with Functional Maps by embedding the input shapes into an intrinsic-extrinsic product space. Moreover, we disambiguate intrinsic symmetries by applying a surrogate based Markov chain Monte Carlo initialization. Our method naturally handles various types of noise that commonly occur in real scans, like non-isometry or incompatible meshing. Finally, we demonstrate state-of-the-art quantitative results on several datasets and show that our pipeline produces smoother, more realistic results than other automatic matching methods in real world applications.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex

    @InProceedings{eisenberger2020smoothshells,
        author 	= {Marvin Eisenberger and Zorah L\"ahner and Daniel Cremers},
        title 	= {Smooth Shells: Multi-Scale Shape Registration with Functional Maps},
        booktitle    	= {Conference on Computer Vision and Pattern Recognition (CVPR)},
        year 		= {2020},
        month 	= {June},
    }
