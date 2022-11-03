# Image_compression_using_k_means_clustering_algorithm: In this project, I'll implement the k-means clustering algorithm and use it for image compression! I will start with a sample dataset that will help me gain an intuition of how the K-means algorithm works.
After that, I will use the K-means algorithm for image compression by reducing the number of colors that occur in an image to only those that are most common in that image.


#Anomaly_detection_algorithm_to_identify_potentially_failing(anomalous)_servers: In this project, I will implement the anomaly detection algorithm and apply it to monitor computer servers to identify potentially failing (anomalous) servers.
I will implement an anomaly detection algorithm to detect anomalous behavior in server computers.The dataset contains two features -
throughput (mb/s) and
latency (ms) of response of each server.
While the servers were operating, I collected  𝑚=307  examples of how they were behaving, and thus have an unlabeled dataset  {𝑥(1),…,𝑥(𝑚)} .

I suspect that the vast majority of these examples are “normal” (non-anomalous) examples of the servers operating normally, but there might also be some examples of servers acting anomalously within this dataset.
I will use a Gaussian model to detect anomalous examples in the dataset.

I will first start on a 2D dataset that will allow to visualize what the algorithm is doing.
On that dataset I will fit a Gaussian distribution and then find values that have very low probability and hence can be considered anomalies.
After that, I will apply the anomaly detection algorithm to a larger dataset with many dimensions.
