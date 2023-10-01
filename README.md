# Size_Contrained_KMeans
Solving the problem "Star maps 2.0" with Yandex ML competition 2022. In the stellar galaxy, 9604 images were sent over a noisy channel. It is necessary to divide all the images into 983 clusters, it is known that each cluster contains from 7 to 10 images.
## Methods
1. Using a pre-trained VGG16, VG19, ResNet50 to get image embeddings
2. PCA
3. Implementation of Size Contrained KMeans https://github.com/jingw2/size_constrained_clustering
## Metrics
Accuracy
