---
title: "Mixtures of All Trees"
collection: publications
permalink: /publication/moat
excerpt: '**Nikil Roashan Selvam**, Honghua Zhang, and Guy Van den Broeck'
date: 2023-03-01
venue: 'Proceedings of the 25th International Conference on Artificial Intelligence and Statistics (AISTATS)'
paperurl: 'http://nikilrselvam.github.io/files/SelvamAISTATS23.pdf'
codeurl: 'https://github.com/UCLA-StarAI/MoAT'
biburl: 'https://nikilrselvam.github.io/files/SelvamAISTATS23.bib'
---
**Nikil Roashan Selvam**, Honghua Zhang, and Guy Van den Broeck
## Abstract 
Tree-shaped graphical models are widely used for their tractability. However, they unfortunately lack expressive power as they require committing to a particular sparse dependency structure. We propose a novel class of generative models called mixtures of all trees: that is, a mixture over all possible (nn−2) tree-shaped graphical models over n variables. We show that it is possible to parameterize this Mixture of All Trees (MoAT) model compactly (using a polynomial-size representation) in a way that allows for tractable likelihood computation and optimization via stochastic gradient descent. Furthermore, by leveraging the tractability of tree-shaped models, we devise fast-converging conditional sampling algorithms for approximate inference, even though our theoretical analysis suggests that exact computation of marginals in the MoAT model is NP-hard. Empirically, MoAT achieves state-of-the-art performance on density estimation benchmarks when compared against powerful probabilistic models including hidden Chow-Liu Trees.
[PDF](http://nikilrselvam.github.io/files/SelvamAISTATS23.pdf)
[Code](https://github.com/UCLA-StarAI/MoAT)
[BibTex](https://nikilrselvam.github.io/files/SelvamAISTATS23.bib)
