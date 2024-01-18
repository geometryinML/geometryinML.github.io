---
title: "Q-Match: Iterative Shape Matching via Quantum Annealing"
collection: publications
permalink: /publication/2021-iccv-q-match-iterative-shape-matching-via-quantum-annealing
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2021-09-01
venue: 'International Conference on Computer Vision (ICCV)'
paperurl: 'http://zorah.github.io/files/pdfs/seelbach2021qmatch.pdf'
authors: 'Marcel Seelbach Benkner, <b>Zorah Lähner</b>, Vladislav Golyanik, Christof Wunderlich, Christian Theobalt, Michael Moeller'
teaser: /previews/seelbach2021qmatch.png
arxiv: 'https://arxiv.org/abs/2105.02878'
code: https://github.com/MSeelbach/Q-Match
categories: [correspondence, quantum]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/seelbach2021qmatch.png" alt="Teaser Image" title="teaser" />

## Abstract

> Finding shape correspondences can be formulated as an NP-hard quadratic assignment problem (QAP) that becomes infeasible for shapes with high sampling density. A promising research direction is to tackle such quadratic optimization problems over binary variables with quantum annealing, which, in theory, allows to find globally optimal solutions relying on a new computational paradigm. Unfortunately, enforcing the linear equality constraints in QAPs via a penalty significantly limits the success probability of such methods on currently available quantum hardware. To address this limitation, this paper proposes Q-Match, i.e., a new iterative quantum method for QAPs inspired by the alpha-expansion algorithm, which allows solving problems of an order of magnitude larger than current quantum methods. It works by implicitly enforcing the QAP constraints by updating the current estimates in a cyclic fashion. Further, Q-Match can be applied for shape matching problems iteratively, on a subset of well-chosen correspondences, allowing us to scale to real-world problems. Using the latest quantum annealer, the D-Wave Advantage, we evaluate the proposed method on a subset of QAPLIB as well as on isometric shape matching problems from the FAUST dataset.


## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex

    @InProceedings{seelbach2021qmatch,
        author 	= "Marcel {Seelbach Benkner} and Zorah L\"ahner and Vladislav Golyanik and Christof Wunderlich and Christian Theobalt and Michael Moeller",
        title 	= "Q-Match: Iterative Shape Matching via Quantum Annealing",
        booktitle    	= "International Conference on Computer Vision (ICCV)",
        year 		= "2021",
    }
