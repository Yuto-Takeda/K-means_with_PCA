# Overview
This is the practice project for K-means and PCA. I used the synthetic dataset with 500 features. 

If we compare the SSE from the k-means without PCA and the one with PCA, we can describe that for any k, the SSE is smaller in the result of k-means clustering with PCA. 
In fact, even when k=0 at k-means clustering with PCA, SSE was 960,000. However, when k=0 at k-means clustering without PCA, SSE was 1,300,000.

Number of K vs SSE (without PCA)

<img src="https://user-images.githubusercontent.com/79394001/233885960-13b03b25-a3b6-4c73-ae10-108b41a0fd57.png" width="500">


Cumulative variance plot of PCA components

<img src="https://user-images.githubusercontent.com/79394001/233886299-42d2902a-7f10-4995-bb6c-643f6ca566a1.png" width="500">


Number of K vs SSE (with PCA)

<img src="https://user-images.githubusercontent.com/79394001/233886350-61a5b376-3d96-43a0-a667-bb4c7106b038.png" width="500">
