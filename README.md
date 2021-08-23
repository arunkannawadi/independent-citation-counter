
# Independent citation counter

A (collection of) Jupyter notebook(s) that count independent citations from different bibliographic databases:
- SAO/NASA Astrophysics Data System (ADS)  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/arunkannawadi/independent-citation-counter/blob/master/ads.ipynb)
- Google Scholar (coming soon)

## What are independent citations?

A citation to a paper is an independent citation if the citing paper and the cited paper share no common authors.

The number of independent citations of an author is simply the sum of the number of independent citations of all papers written by that author.
This is less restrictive than the definition where citations by those who have never written a paper together with the author.

## Why?

Some application packages need to exclude all counts of self-citations to evaluate the impact of one's research.