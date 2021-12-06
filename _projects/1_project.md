---
layout: page
title: conditional sampling
description: We can use a generative model as a prior for decomposing a linear mixture of sources into its constituent parts. We demonstrate this on the left for linearly superimposed images of churches and bedrooms. The idea is to train train two generative models&#58; one that estimates the likelihood of the distribution over images of churches, and another that does the same for images of bedrooms. We can separate a mixture of images by decomposing it into two images that are likely under the priors for churches and bedrooms respectively, that satisfy the constraint that decomposition must sum to the given mixture. This can be interpreted as conditional sampling from the posterior distribution over sources given a mixture. Our work on visual source separation has appeared at ICML 2020. Extensions of these results to audio separation and more general conditional sampling problems appeared at ICML 2021.
img: assets/img/lsun_sep.png
redirect: https://grail.cs.washington.edu/projects/pnf-sampling/
importance: 2
category: work
---

