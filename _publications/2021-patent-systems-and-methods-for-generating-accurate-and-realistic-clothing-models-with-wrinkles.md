---
title: "Systems and Methods for Generating Accurate and Realistic Clothing Models with Wrinkles"
collection: publications
permalink: /publication/2021-patent-systems-and-methods
date: 2021-10-26
venue: 'US Patent 11158121'
paperurl: 'https://patents.google.com/patent/US11158121B1/en'
authors: 'Tony Tung, <b>Zorah Lähner</b>'
teaser: /previews/laehner2018deepwrinkles.png
bibtex: true
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/laehner2018deepwrinkles.png" alt="Teaser Image" title="teaser" />

## Abstract

> In one embodiment, a computing system may be configured to generate accurate and realistic computer-generated clothing for a given body pose. For example, the system may access a data representation of a body pose and generate, based on the data representation, a 3D clothing model for the body pose using a statistical model. The system may generate a first normal map, such as a low-resolution normal map, based on the 3D clothing model. The system may generate a second normal map, such as a high-resolution normal map, by processing the first normal map using a machine-learning model that is trained to generate normal maps with higher levels of detail from normal maps with relatively lower levels of detail. The system may then render clothing for the body pose based on the 3D clothing model and the second normal map.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex

    @misc{tung2021systems,
        author 	= "Tony Tung and Zorah L\"ahner",
        title 	= "Systems and Methods for Generating Accurate and Realistic Clothing Models with Wrinkles",
        howpublished = "US Patent 11158121",
        month        = "October",
        year         = "2021",
    }
