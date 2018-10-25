---
permalink: /tools/
title: "Tools"
excerpt: "Tools"
author_profile: true
---

I have built a number of tools to support my research. All are functional, though documentation is in varying stages of completion. Feel free to contact me if you want more information.

## Nama
Nama (NAme-MAtcher) is a powerful tool for matching names and clustering names. It integrates multiple types of fuzzy matching, including a novel neural network algorithm for quickly finding potential matches, and provides tools for reviewing, modifying, and iteratively improving matches. [View on GitHub](https://github.com/bradhackinen/nama)

## Subex
Subex (SUbstring-EXtractor) is a tool for extracting parts of strings using a trainable recurrent neural network. It achieved 97% accuracy on the task of identifying organization names in comment titles and other metadata from regulations.gov (for my job market paper). [View on GitHub](https://github.com/bradhackinen/subex)

## Non-parametric Plots
A collection of non-parametric regression plots to fill some gaps in the Python plotting universe. Includes a Loess plots, locally smoothed heatmaps, and local correlation plots. [View on GitHub](https://github.com/bradhackinen/nonparametricPlots)

## Vectorized MinHash
A small toolkit for very efficiently comparing the similarity of large numbers of documents or other data structures that can be represented as sets. The core MinHash algorithm is vectorized in numpy and includes CUDA support via cupy. Also includes a bias-corrected MLE estimator of cardinality (which is a significant improvement over other Python implementations) and tools for fast conversion of text to n-grams. [View on GitHub](https://github.com/bradhackinen/vectorizedMinHash)

## federalRegister
My interface for collecting and parsing Federal Register documents.
[View on GitHub](https://github.com/bradhackinen/federalRegister)
