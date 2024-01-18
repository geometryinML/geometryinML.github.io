---
title: "Kissing to Find a Match: Efficient Low-Rank Permutation Representation"
collection: publications
permalink: /publication/2023-arxiv-kissing-match
excerpt: 'Permutation matrices play a key role in matching and assignment problems across the fields, especially in computer vision and robotics. However, memory for explicitly representing permutation matrices grows quadratically with the size of the problem, prohibiting large problem instances. In this work, we propose to tackle the curse of dimensionality of large permutation matrices by approximating them using low-rank matrix factorization, followed by a nonlinearity. To this end, we rely on the Kissing number theory to infer the minimal rank required for representing a permutation matrix of a given size, which is significantly smaller than the problem size. This leads to a drastic reduction in computation and memory costs, e.g., up to 3 orders of magnitude less memory for a problem of size n = 20000, represented using 8.4 × 105 elements in two small matrices instead of using a single huge matrix with 4 × 108 elements. The proposed representation allows for accurate representations of large permutation matrices, which in turn enables handling large problems that would have been infeasible otherwise. We demonstrate the applicability and merits of the proposed approach through a series of experiments on a range of problems that involve predicting permutation matrices, from linear and quadratic assignment to shape matching problems.'
date: 2023-12-10
venue: 'Neural Information Processing Systems (NeuRIPS)'
authors: 'Hannah Dröge, <b>Zorah Lähner</b>, Yuval Bahat, Onofre Martorell, Felix Heide, Michael Moeller'
teaser: /previews/droege2023kissing.png
arxiv: 'https://arxiv.org/abs/2308.13252'
paperurl: 'http://zorah.github.io/files/pdfs/droege2023kissing.pdf'
categories: [geometricDL,correspondence]
code: 'https://github.com/drgHannah/Kissing-to-Find-a-Match'
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/droege2023kissing.png" alt="Teaser Image" title="teaser" />

## Abstract

> Permutation matrices play a key role in matching and assignment problems across the fields, especially in computer vision and robotics. However, memory for explicitly representing permutation matrices grows quadratically with the size of the problem, prohibiting large problem instances. In this work, we propose to tackle the curse of dimensionality of large permutation matrices by approximating them using low-rank matrix factorization, followed by a nonlinearity. To this end, we rely on the Kissing number theory to infer the minimal rank required for representing a permutation matrix of a given size, which is significantly smaller than the problem size. This leads to a drastic reduction in computation and memory costs, e.g., up to 3 orders of magnitude less memory for a problem of size n = 20000, represented using 8.4 × 105 elements in two small matrices instead of using a single huge matrix with 4 × 108 elements. The proposed representation allows for accurate representations of large permutation matrices, which in turn enables handling large problems that would have been infeasible otherwise. We demonstrate the applicability and merits of the proposed approach through a series of experiments on a range of problems that involve predicting permutation matrices, from linear and quadratic assignment to shape matching problems.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}


## Bibtex

    @inproceedings{droege2023kissing,
        author 	= {Hannah Dr\"oge and Zorah L\"ahner and Yuval Bahat and Onofre Martorell and Felix Heide and Michael Moeller},
        title 	= { Kissing to Find a Match: Efficient Low-Rank Permutation Representation },
        booktitle = {Neural Information Processing Systems (NeuRIPS)},
        year 	= 2023,
    }
