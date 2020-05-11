# K_Medoid_Clustering

In this project I revisit __clustering__, one of my favourite analytic methods, to explore and analyse a real-world dataset that included a __mix of categorical and numerical__ feature. This required a different approach from the classical __K-means__ algorithm that cannot be no directly applied to categorical data. 

Instead, I used the __K-medoids__ algorithm, also known as __PAM__ (Partitioning Around Medoids), that has the advantage of working on __distances other than numerical__ and lends itself well to analyse mixed-type data. 

The __silhouette coefficient__ helped to establish the __optimal number of clusters__, whilst __t-SNE__ ( t-distributed stochastic neighbour embedding), a dimensionality reduction technique akin _Principal Component Analysis_ and _UMAP_, unveiled __good separation between clusters__ as well as __closeness of elements within clusters__, confirming the segmentation relevance.

Finally, I condensed the __insight__ generated from the analysis into a number of actionable and __data-driven recommendations__ that, applied correctly, could __help improve product sign up__.
