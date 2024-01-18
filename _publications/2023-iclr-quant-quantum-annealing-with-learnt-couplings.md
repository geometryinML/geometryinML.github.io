---
title: "QuAnt: Quantum Annealing with Learnt Couplings"
collection: publications
permalink: /publication/2023-iclr-quant
excerpt: 'Modern quantum annealers can find high-quality solutions to combinatorial optimisation objectives given as quadratic unconstrained binary optimisation (QUBO) problems. Unfortunately, obtaining suitable QUBO forms in computer vision remains challenging and currently requires problem-specific analytical derivations. Moreover, such explicit formulations impose tangible constraints on solution encodings. In stark contrast to prior work, this paper proposes to learn QUBO forms from data through gradient backpropagation instead of deriving them. As a result, the solution encodings can be chosen flexibly and compactly. Furthermore, our methodology is general and virtually independent of the specifics of the target problem type. We demonstrate the advantages of learnt QUBOs on the diverse problem types of graph matching, 2D point cloud alignment and 3D rotation estimation. Our results are competitive with the previous quantum state of the art while requiring much fewer logical and physical qubits, enabling our method to scale to larger problems.'
date: 2023-05-01
venue: 'International Conference on Learning Representations (ICLR)'
authors: 'Marcel Seelbach Benkner, Maximilian Krahn, Edith Tretschk, <b>Zorah Lähner</b>, Michael Moeller, Vladislav Golyanik'
teaser: /previews/seelbach2022quant.png
arxiv: 'https://arxiv.org/abs/2210.08114'
paperurl: 'http://zorah.github.io/files/pdfs/seelbach2022quant.pdf'
code: 'https://github.com/MSeelbach/QuAnt'
categories: [quantum]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/seelbach2022quant.png" alt="Teaser Image" title="teaser" />

## Abstract

> Modern quantum annealers can find high-quality solutions to combinatorial optimisation objectives given as quadratic unconstrained binary optimisation (QUBO) problems. Unfortunately, obtaining suitable QUBO forms in computer vision remains challenging and currently requires problem-specific analytical derivations. Moreover, such explicit formulations impose tangible constraints on solution encodings. In stark contrast to prior work, this paper proposes to learn QUBO forms from data through gradient backpropagation instead of deriving them. As a result, the solution encodings can be chosen flexibly and compactly. Furthermore, our methodology is general and virtually independent of the specifics of the target problem type. We demonstrate the advantages of learnt QUBOs on the diverse problem types of graph matching, 2D point cloud alignment and 3D rotation estimation. Our results are competitive with the previous quantum state of the art while requiring much fewer logical and physical qubits, enabling our method to scale to larger problems. 

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

The official project page is <a href="https://4dqv.mpi-inf.mpg.de/QuAnt/">here</a>.

## Bibtex

    @inproceedings{seelbach2022quant,
        author 	= {Marcel Seelbach Benkner and Maximilian Krahn and Edith Tretschk and Zorah L\"ahner and Michael Moeller and Vladislav Golyanik},
        title 	= { {QuAnt}: Quantum Annealing with Learnt Couplings},
        booktitle = {International Conference on Learning Representations (ICLR)},
        year 	= 2023,
    }
