# Clustering-Crypto
PCA and clustering using K-Means (sklearn)

### Background Scenario

A prominent investment bank, is interested in offering a new cryptocurrencies investment portfolio for its customers, however, they are lost in the immense universe of cryptocurrencies. They are looking for informationthat would help them make sense of it all by generating a report of what cryptocurrencies are available on the trading market and how they can be grouped using classification.  

In this project, unsupervivsed learning and Amazon SageMaker skills are used to cluster cryptocurrencies and create plots to present results.

Following are the steps:

* **[Data Preprocessing](#Data-Preprocessing):** Prepare data for dimension reduction with PCA and clustering using K-Means.

* **[Reducing Data Dimensions Using PCA](#Reducing-Data-Dimensions-Using-PCA):** Reduce data dimension using the `PCA` algorithm from `sklearn`.

* **[Clustering Cryptocurrencies Using K-Means](#Clustering-Cryptocurrencies-Using-K-Means):** Predict clusters using the cryptocurrencies data using the `KMeans` algorithm from `sklearn`.

* **[Visualizing Results](#Visualizing-Results):** Create some plots and data tables to present your results.

* **[Optional Challenge](#Optional-Challenge):** Deploy your notebook to Amazon SageMaker.

---

### Files

* [crypto_clustering.ipynb](crypto_clustering.ipynb)


### Clustering Crytocurrencies Using K-Means

#### Find the Best Value for `k` Using the Elbow Curve

![image](https://user-images.githubusercontent.com/51159089/140621962-1d348600-91a7-4c7a-92af-085a366301da.png)


### Visualizing Results

#### 3D-Scatter with Clusters

![image](https://user-images.githubusercontent.com/51159089/140621991-265bded5-298e-40ee-8ecd-c0499714d628.png)


#### Scatter Plot with Tradable Cryptocurrencies

![image](https://user-images.githubusercontent.com/51159089/140622014-bf5c1430-d2a5-45be-808f-8e0f5ce57f8d.png)


