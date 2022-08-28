# Sirius, 2021
## Semantic extraction and synthesis project (Huawei)

All presentation is available in final_presentation.pdf

### Embeddings clusterization
We were studying the clusterization methods and show that there exist clusters in the embeddings data. Perform the visualization of these data clusters.

![](/images/plot_clusters.png)

Also we noticed that Deep embedded clustering model get better results that other clustering methods such as K-means or even clusterazation via autoencoder.

### CLIP Latent space with CelebA dataset
We get CLIP latent vectors for images from CelebA dataset and want to understand which elements of this vectors match image features. We found some of this dependencies. We can add glasses, change skin color and sex.

###  Glasses
The first line contains the original images, the next two lines contain the modified ones. In this example, we change the components of the factorized vector and as a result we get photos of people with glasses.
![](/images/glasses.png)

### Skin
By changing another component of the vector, the race of the people in the pictures changes.
![](/images/skin.png)

### Sex
By changing the component of the vector, we can also change the gender of a person
![](/images/sex2.png)

### CLIP check
In the CLIP model, we can compare a text string with an image and determine how close they are to each other. With this we can check that semantic features have indeed been changed. 
![](/images/photo_2021-08-05_20-20-01.jpg)

