## Intro of the Clustering
![alt][image.png]
![alt text](image-1.png)
 

 ## K-means
 
 Repeat these two steps
![alt text](image-4.png)


![alt text](image-2.png)

![alt text](image-3.png)
![alt text](image-5.png)

K-means is sensitive to how the initial cluster centroids are chosen. A bad initialization can lead to local minima (poor clustering results with high distortion/cost). Instead of running K-means once, we run it many times (e.g., 100, or even 50–1000 times):
![alt text](image-6.png)
![alt text](image-7.png)

(./K-means.ipynb)


