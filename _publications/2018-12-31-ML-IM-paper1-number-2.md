---
title: "Deconfusing intensity maps with neural networks"
collection: publications
permalink: /publication/CNN-LIM
excerpt: 'In this work we present the first application of convolutional neural network (CNN) to directly determine the underlying luminosity function of a LIM, including a treatment of extragalactic foregrounds and instrumental noise.'
date: 2019-5-17
venue: 'Journal 1'
paperurl: 'https://arxiv.org/abs/1905.XXXXX'
citation: 'D. N. Pfeffer, P. C. Breysse and G. Stein, Mon. Not. Roy. Astron. Soc. ???, no. ?, ??? (2019)'
---
Line intensity maps (LIMs) are in principle sensitive to a large amount of information about faint, distant galaxies which are invisible to conventional surveys. However, actually extracting that information from a confused, foreground-contaminated map can be challenging.  In this work we present the first application of convolutional neural network (CNN) to directly determine the underlying luminosity function of a LIM, including a treatment of extragalactic foregrounds and instrumental noise. We apply the CNN to simulations of mock Carbon Monoxide (CO) line intensity maps similar to those which will be produced by the currently-active COMAP experiment. We evaluate the trained CNN on a number of noise scenarios in order to determine how robust the network predictions are for application to realistic data. We find that, in the ideal case where the mock data capture all of the features of the real data, the CNN performs comparably to or better than conventional analyses.  However, the network's accuracy degrades considerably when tested on signals and systematics outside of those it was trained on.  For both intensity mapping and cosmology as a whole, this motivates a broad-based study of whether simulated data can ever be generated with sufficient detail to realize the enormous potential of machine learning methods.

Tools used to train the CNN are found in [this repository](https://github.com/dnpfeffer/intensitymap_cnn)

[Download paper here](http://dnpfeffer.github.io/files/paper2.pdf)
