---
title: "Efficient Globally Optimal 2D-to-3D Deformable Shape Matching"
collection: publications
permalink: /publication/2016-cvpr-efficient-globally-optimal-2d-to-3d-deformable-shape-matching
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2016-06-01
venue: 'Conference on Computer Vision and Pattern Recognition (CVPR)'
paperurl: 'http://zorah.github.io/files/pdfs/laehner2016elastic2D3D.pdf'
authors: '<b>Zorah Lähner</b>, Emanuele Rodolà, Frank R. Schmidt, Michael M. Bronstein, Daniel Cremers'
teaser: /previews/laehner2016elastic2D3D.png
arxiv: 'https://arxiv.org/abs/1601.06070'
code: https://github.com/zorah/Elastic2D3D
categories: [correspondence, dataset]
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/laehner2016elastic2D3D.png" alt="Teaser Image" title="teaser" />

## Abstract

> We propose the first algorithm for non-rigid 2D-to-3D shape matching, where the input is a 2D query shape as well as a 3D target shape and the output is a continuous matching curve represented as a closed contour on the 3D shape. We cast the problem as finding the shortest circular path on the product 3-manifold of the two shapes. We prove that the optimal matching can be computed in polynomial time with a (worst-case) complexity of O(mn^2 log(n)), where m and n denote the number of vertices on the 2D and the 3D shape respectively. Quantitative evaluation confirms that the method provides excellent results for sketch-based deformable 3D shape retrieval.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}


**Data**

[(dataset parameter tuning, 2.7GB)](https://www.dropbox.com/s/b8pp46ssbm774pf/faust.zip?dl=0) based on [MPI FAUST](http://faust.is.tue.mpg.de/)

[(dataset retrieval, 2.9GB)](https://www.dropbox.com/s/bfqghkp24gk7ni6/retrieval.zip?dl=0) based on [TOSCA high-res](http://tosca.cs.technion.ac.il/book/resources_data.html)

[(retrieval matchings, 267kB)](https://www.dropbox.com/s/kkd2bfbo42ze6sb/results.zip?dl=0)

**Additional Code**

[(matching code, 281MB)](https://www.dropbox.com/s/gejbfyfnuorerc9/code_Elastic2D3D.zip?dl=0) Matlab/C++ Code, example with precomputed data reproducing one matching

[(retrieval code, 270kB)](https://www.dropbox.com/s/ymcku6c21d93bdp/retrieval_code_2D3D.zip?dl=0) Matlab Code, code outline to run retrieval on a new data set, needs matching code

## Bibtex

    @InProceedings{laehner2016elastic2D3D,
      author       = {Zorah L\"ahner and Emanuele Rodol\`a and Frank R. Schmidt and Michael M. Bronstein and Daniel Cremers},
      title        = { Efficient Globally Optimal 2D-to-3D Deformable Shape Matching },
      booktitle    = { Proc. of IEEE Conference on Computer Vision and Pattern Recognition (CVPR) },
      month        = { June },
      year         = { 2016 },
    }
