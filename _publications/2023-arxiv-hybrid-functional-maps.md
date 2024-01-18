---
title: "Hybrid Functional Maps for Crease-Aware Non-Isometric Shape Matching"
collection: publications
permalink: /publication/2023-arxiv-hybrid-functional-maps
excerpt: 'Non-isometric shape correspondence remains a fundamental challenge in computer vision. Traditional methods using Laplace-Beltrami operator (LBO) eigenmodes face limitations in characterizing high-frequency extrinsic shape changes like bending and creases. We propose a novel approach of combining the non-orthogonal extrinsic basis of eigenfunctions of the elastic thin-shell hessian with the intrinsic ones of the LBO, creating a hybrid spectral space in which we construct functional maps. To this end, we present a theoretical framework to effectively integrate non-orthogonal basis functions into descriptor- and learning-based functional map methods. Our approach can be incorporated easily into existing functional map pipelines across varying applications and is able to handle complex deformations beyond isometries. We show extensive evaluations across various supervised and unsupervised settings and demonstrate significant improvements. Notably, our approach achieves up to 15% better mean geodesic error for non-isometric correspondence settings and up to 45% improvement in scenarios with topological noise.'
date: 2023-12-20
venue: 'arXiv'
authors: 'Lennart Bastian*, Yizheng Xie*, Nassir Navab, <b>Zorah Lähner</b>'
teaser: /previews/bastian2023hybrid.png
categories: [geometricDL,correspondence]
arxiv: https://arxiv.org/abs/2312.03678
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/bastian2023hybrid.png" alt="Teaser Image" title="teaser" />

## Abstract

> With the wide adaption of deep learning and pre-trained models rises the question of how to effectively reuse existing latent spaces for new applications. One important question is how the geometry of the latent space changes in-between different training runs of the same architecture and different architectures trained for the same task. Previous works proposed that the latent spaces for similar tasks are approximately isometric. However, in this work we show that method restricted to this assumption perform worse than when just using a linear transformation to align the latent spaces. We propose directly computing a transformation between the latent codes of different architectures which is more efficient than previous approaches and flexible wrt. to the type of transformation used. Our experiments show that aligning the latent space with a linear transformation performs best while not needing more prior knowledge.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}


## Bibtex

    @inproceedings{bastian2023hybrid,
        author 	= {Lennart Bastian and Yizheng Xie and Nassir Navab and Zorah Lähner},
        title 	= { Hybrid Functional Maps for Crease-Aware Non-Isometric Shape Matching },
        booktitle = {arxiv:2312.03678},
        year 	= 2023,
    }
