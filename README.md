# Visualisation_methods

Comparison of TSNE UMAP and LargeVis

## Description

This project compares three visualisation methods: t-SNE, UMAP and LargeVis.

  #### t-SNE: T-distributed Stochastic Neighbor Embedding

t-SNE is a tool to visualize high-dimensional data. It converts similarities between data points to joint probabilities and tries to minimize the Kullback-Leibler divergence between the joint probabilities of the low-dimensional embedding and the high-dimensional data. t-SNE has a cost function that is not convex, i.e. with different initializations we can get different results. Source: https://scikit-learn.org/stable/modules/generated/sklearn.manifold.TSNE.html



   #### UMAP: Uniform Manifold Approximation and Projection for Dimension Reduction

Uniform Manifold Approximation and Projection (UMAP) is a dimension reduction technique that can be used for visualisation similarly to t-SNE, but also for general non-linear dimension reduction. 
Source: https://umap-learn.readthedocs.io/en/latest/index.html


  #### LargeVis

LargeVis is a clever method that allows a t-SNE like visualization using stochastic gradient descent, which scales much better than the Barnes-Hut approximation to t-SNE. LargeVis does not minimize the same cost function as t-SNE, but it is similar. 
Source: https://github.com/lferry007/LargeVis
###### Note: To plot the LargeVis embending we need to read the mnist/fmnist_vis_out.txt files.


