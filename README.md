# Human-Activity-Recognition

The Human Activity Recognition dataset was built from the recordings of 30 study participants performing activities of daily living (ADL).
Each participants performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S Il) on the waist. Using its embedded accelerometer and gyroscope, 3-axial linear acceleration and
3-axial angular velocity were captured at a constant rate of 50Hz.

## Task 1: Data Loading and Scaling
1. Load the data.
2. Scale the data using Z-mean standardization.

## Task 2: PCA
3. Run PCA using scaled data, leaving as many components as necessary to explain at least 95% of the variance of the original (scaled) data.
4. Print the minimum number of PCs required to cover the 95% of the variance of the original (scaled) data.
5. Plot the cumulative explained variance vs. the number of principal components.
6. Print the percentage of the variance that is covered by the first and second PCs.
7. Visualize the data in the projection of the first two main components and color the dots according to the class labels.
8.Based on the PCA plot, how many clusters do you have that are almost perfectly separated from each other. What types of activity are included in these clusters? Is there an explanation for that?

## Task 3: Clustering
9. Cluster the reduced data using the Means into 6 clusters same as the number of classes.
10. Visualize the data in the projection on the first two PCs and color the dots according to the generated clusters using clustering result of (9).
11. Compare the result of clustering with the original class labels using confusion matrix and identify the activities that cannot be distinguished using Kmeans (Print the confusion matrix).
12. Cluster the reduced data using agglomerative clustering with ward linkage and the number of clusters = 6.
13. Cluster the reduced data using spectral clustering where the number of clusters = 6
14. Compare the results of means, agglomerative clustering, and spectral clustering using ARI and silhouette coefficient.
15. Use the elbow method to find the optimal number of clusters using K-means where K ranges from 1 to 10.

## Data Used:
HAR_labels.txt and HAR_data.txt (uploaded)

### Built With:

<img width="40" alt="logo" src="https://user-images.githubusercontent.com/98522684/200248160-e3e79aa5-863e-4616-a11e-823866901875.png">
