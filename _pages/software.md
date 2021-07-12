---
permalink: /software/
title: "Software"
excerpt: "Software"
author_profile: true
---

I have built a number of software tools to support my research. All are functional, though the documentation is in varying stages of completion. Feel free to [contact me](mailto:bradhackinen@gmail.com) if you want more information.

**[nama](https://github.com/bradhackinen/nama)**<\br>
Nama (NAme-MAtcher) is a powerful tool for matching and clustering names in very large datasets. It integrates multiple types of fuzzy matching, including a novel neural network algorithm for quickly finding potential matches, and provides tools for reviewing, modifying, and iteratively improving matches.

**[vminhash](https://github.com/bradhackinen/vminhash)**<\br>
A small toolkit for very efficiently comparing the similarity, clustering, and identifying duplicates within of large sets of documents. The core MinHash algorithm is vectorized in numpy and includes CUDA support via cupy. Also includes a bias-corrected MLE estimator of cardinality (which is a significant improvement over other Python implementations).

**[frdocs](https://github.com/bradhackinen/frdocs)**<\br>
My interface for collecting and parsing Federal Register documents.
