---
title: "DeepWrinkles: Accurate and Realistic Clothing Modeling"
collection: publications
permalink: /publication/2018-eccv-deepwrinkles-accurate-and-realistic-clothing-modeling
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2018-09-01
venue: 'European Conference on Computer Vision (ECCV)'
paperurl: 'http://zorah.github.io/files/pdfs/laehner2018deepwrinkles.pdf'
authors: '<b>Zorah Lähner</b>, Daniel Cremers, Tony Tung'
teaser: /previews/laehner2018deepwrinkles.png
arxiv: 'https://arxiv.org/abs/1808.03417'
video: https://www.youtube.com/watch?v=g2hmNE1AxjQ
categories: [geometricDL]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/laehner2018deepwrinkles.png" alt="Teaser Image" title="teaser" />

## Abstract

> We present a novel method to generate accurate and realistic clothing deformation from real data capture. Previous methods for realistic cloth modeling mainly rely on intensive computation of physics-based simulation (with numerous heuristic parameters), while models reconstructed from visual observations typically suffer from lack of geometric details. Here, we propose an original framework consisting of two modules that work jointly to represent global shape deformation as well as surface details with high fidelity. Global shape deformations are recovered from a subspace model learned from 3D data of clothed people in motion, while high frequency details are added to normal maps created using a conditional Generative Adversarial Network whose architecture is designed to enforce realism and temporal consistency. This leads to unprecedented high-quality rendering of clothing deformation sequences, where fine wrinkles from (real) high resolution observations can be recovered. In addition, as the model is learned independently from body shape and pose, the framework is suitable for applications that require retargeting (e.g., body animation). Our experiments show original high quality results with a flexible model. We claim an entirely data-driven approach to realistic cloth wrinkle generation is possible.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex

    @InProceedings{laehner2018deepwrinkles,
        author 	= "Z. L\"ahner and D. Cremers and T. Tung",
        title 	= "DeepWrinkles: Accurate and Realistic Clothing Modeling",
        booktitle    	= "European Conference on Computer Vision (ECCV)",
        year 		= "2018",
        month 	= "September",
    }
