---
title: "A Network Analysis for Correspondence Learning via Linearly-Embedded Functions"
collection: publications
permalink: /publication/2023-gcpr-network
excerpt: 'Calculating correspondences between non-rigidly deformed shapes is the backbone of many applications in 3D computer vision and graphics.
The functional map approach offers an efficient solution to this problem and has been very popular in learning frameworks due to its low-dimensional and continuous nature. However, most methods rely on the eigenfunctions of the Laplace-Beltrami operator as a basis for the underlying function spaces. While these have many advantages, they are also sensitive to non-isometric deformations and noise. Recently a method to learn the basis functions along with suitable descriptors has been proposed by Marin et al. We do an in-depth analysis of the architecture proposed, including a new training scheme to increase robustness against sampling inconsistencies and an extension to unsupervised training which still obtains results on-par with the supervised approach. '
date: 2023-09-20
venue: 'German Conference on Pattern Recognition (GCPR)'
authors: 'Sharik Siddiqi, <b>Zorah Lähner</b>'
teaser: /previews/siddiqi2023network.png
paperurl: 'http://zorah.github.io/files/pdfs/siddiqi2023unsupervised.pdf'
categories: [correspondence,geometricDL]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/siddiqi2023network.png" alt="Teaser Image" title="teaser" />

## Abstract

> Calculating correspondences between non-rigidly deformed shapes is the backbone of many applications in 3D computer vision and graphics.
The functional map approach offers an efficient solution to this problem and has been very popular in learning frameworks due to its low-dimensional and continuous nature. However, most methods rely on the eigenfunctions of the Laplace-Beltrami operator as a basis for the underlying function spaces. While these have many advantages, they are also sensitive to non-isometric deformations and noise. Recently a method to learn the basis functions along with suitable descriptors has been proposed by Marin et al. We do an in-depth analysis of the architecture proposed, including a new training scheme to increase robustness against sampling inconsistencies and an extension to unsupervised training which still obtains results on-par with the supervised approach.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex

    @inproceedings{gao2023sigma,
        author 	= { Sharik Siddiqi and Zorah L\"ahner },
        title 	= { A Network Analysis for Correspondence Learning via Linearly-Embedded Functions},
        booktitle = {Accepted to German Conference on Pattern Recognition (GCPR)},
        year 	= 2023,
    }
