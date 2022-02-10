# Text2Landscape

## An R markdown notebook

The core of this repository is an [Rmd notebook](text2landscape.Rmd) that allows you to transform a corpus of texts to a landscape by the tools of computer linguistics, statistics and data visualization packages. Download it and open it in RStudio or VSCode to experiment with the code, or to apply it to your own corpus. Forks and pull requests are welcome!

[See the documentation]().

![](img/network2d3d_2.png)

## Introduction

You will find no realistic landscapes prior to the Renaissance. The
saints of medieval murals float in a conceptual space informed by
hierarchies and symbolic relations; so do those of the Prajñāpāramitā
Sūtras. The word "landscape" appears with the Dutch painters of the 15th
century. A landscape is a part of the world perceived by a human being
at a given moment; an arrangement of features and shapes in a limited
space. The Dutch were focused on natural landscapes. Late 20th-century
urbanism deals with urban landscapes.

A text can be transformed into a landscape by the tools of computer
linguistics, statistics and data visualization packages. Here we work with the example of three texts by the French geographer, writer and anarchist [Élisée
Reclus](https://en.wikipedia.org/wiki/Élisée_Reclus): [Histoire d'une
Montagne](http://www.gutenberg.org/ebooks/60850), [Histoire d'un
ruisseau](https://www.gutenberg.org/ebooks/61697) and
[L'Anarchie](https://www.gutenberg.org/ebooks/40456).

## Visualize the frequencies

![](img/image-7.png)

![](img/image-8.png)

## The Text as a Network of Word Co-occurrence

### Calculate the feature co-occurrence matrix

![](img/image-27.png)

### Visualise the graph

![](img/network2-2.png)

#### 3D variant 
![](img/network3d-3.png)

### Self-organizing map from network

#### From the feature-coocurrence matrix to a positional matrix with multidemensional scaling

![](img/mdsscatter-4.gif)

#### From MDS to SOM

![](img/image-30.png)

![](img/image-31.png)

### The biofabric layout

![](img/image-26.png)

# Word Embeddings

### Principal Component Analysis

![](img/image-17.png)

### Self-organizing Map

![](img/som3d-1.png)