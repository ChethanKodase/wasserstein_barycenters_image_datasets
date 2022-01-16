# Wasserstein barycenters on image datasets

Estimation of the topological features of an underlying manifold of an image dataset could be done using persistence homology. The dataset of images is considered as 
a high dimensional point cloud for which the persistent homology could be calculated. But perisistence homology calculation is very expensive for a large number of images.
Therefor wasserstein barycenters are subsampled from the image dataset. This is done by clustering the similar images by calculating the wasserstein distances between them
and finding out the wasserstein  barycenter of the clustered images. All such wasserstein barycenters sampled are used to calculate persistence homology.
