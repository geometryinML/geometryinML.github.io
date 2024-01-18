---
title: "Isometric Multi-Shape Matching"
collection: publications
permalink: /publication/2021-cvpr-isometric-multi-shape-matching
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2021-06-01
venue: 'Conference on Computer Vision and Pattern Recognition (CVPR)'
paperurl: 'http://zorah.github.io/files/pdfs/gao2021multi.pdf'
authors: 'Maolin Gao, <b>Zorah Lähner</b>, Johan Thunberg, Daniel Cremers, Florian Bernard'
teaser: /previews/gao2021multi.png
arxiv: 'https://arxiv.org/abs/2012.02689'
video: https://www.youtube.com/watch?v=bDy0wHeBeYU
code: https://github.com/maolingao/IsoMuSh
categories: [correspondence]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/gao2021multi.png" alt="Teaser Image" title="teaser" />

## Abstract

> Finding correspondences between shapes is a fundamental problem in computer vision and graphics, which is relevant for many applications, including 3D reconstruction, object tracking, and style transfer. The vast majority of correspondence methods aim to find a solution between pairs of shapes, even if multiple instances of the same class are available. While isometries are often studied in shape correspondence problems, they have not been considered explicitly in the multi-matching setting. This paper closes this gap by proposing a novel optimisation formulation for isometric multi-shape matching. We present a suitable optimisation algorithm for solving our formulation and provide a convergence and complexity analysis. Our algorithm obtains multi-matchings that are by construction provably cycle-consistent. We demonstrate the superior performance of our method on various datasets and set the new state-of-the-art in isometric multi-shape matching.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}


## Bibtex

    @InProceedings{laehner2018gao2021multi,
        author 	= {Maolin Gao and Zorah L\"ahner and Johan Thunberg and Daniel Cremers and Florian Bernard},
        title 	= {Isometric Multi-Shape Matching},
        booktitle    = {Conference on Computer Vision and Pattern Recognition {(CVPR)}},
        year 	= {2021},
        month 	= {June},
    }
