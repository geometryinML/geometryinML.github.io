---
title: "On the Direct Alignment of Latent Spaces"
collection: publications
permalink: /publication/2023-neurips-direct-alignment
excerpt: 'With the wide adaption of deep learning and pre-trained models rises the question of how to effectively reuse existing latent spaces for new applications. One important question is how the geometry of the latent space changes in-between different training runs of the same architecture and different architectures trained for the same task. Previous works proposed that the latent spaces for similar tasks are approximately isometric. However, in this work we show that method restricted to this assumption perform worse than when just using a linear transformation to align the latent spaces. We propose directly computing a transformation between the latent codes of different architectures which is more efficient than previous approaches and flexible wrt. to the type of transformation used. Our experiments show that aligning the latent space with a linear transformation performs best while not needing more prior knowledge.'
date: 2023-12-10
venue: 'NeuRIPS Workshop on Unifying Representations in Neural Models (UniReps)'
authors: '<b>Zorah Lähner</b>, Michael Moeller'
teaser: /previews/laehner2023alignment.png
paperurl: 'http://zorah.github.io/files/pdfs/laehner2023alignment.pdf'
categories: [geometricDL]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/laehner2023alignment.png" alt="Teaser Image" title="teaser" />

## Abstract

> With the wide adaption of deep learning and pre-trained models rises the question of how to effectively reuse existing latent spaces for new applications. One important question is how the geometry of the latent space changes in-between different training runs of the same architecture and different architectures trained for the same task. Previous works proposed that the latent spaces for similar tasks are approximately isometric. However, in this work we show that method restricted to this assumption perform worse than when just using a linear transformation to align the latent spaces. We propose directly computing a transformation between the latent codes of different architectures which is more efficient than previous approaches and flexible wrt. to the type of transformation used. Our experiments show that aligning the latent space with a linear transformation performs best while not needing more prior knowledge.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}


## Bibtex

    @inproceedings{laehner2023alignment,
        author 	= {Zorah L\"ahner and Michael Moeller},
        title 	= { On the Direct Alignment of Latent Spaces },
        booktitle = {NeuRIPS Workshop on Unifying Representations in Neural Models (UniReps)},
        year 	= 2023,
    }
