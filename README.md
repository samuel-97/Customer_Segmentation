This project uses dimensionality reduction and unsupervised learning techniques to cluster a customer data base with the goal of  understanding the customer base and identifying future customers. 

The easy-on-the-eyes report is in Report.pdf. I would recommend that you start there in order to get the gist of the data and the processes I took. 

The actual coding was done in Python and split between 2 different .ipynb files. Analysis cleans, does some preliminary analysis of the data, and finally scales and writes the datasets to 2 different datasets (1 scaled, and one unscaled). 
Segmentation_Recommendation.ipynb is exactly what it says it is. The customer dataset is segmented, analyzed and returns results and a recommendation at the end of the document. 

For a greater understanding of what the Segmentation_Recommendation.ipynb:

The Segmentation_Recommendation.ipynb notebook selects variables that apply to the customers buying habits. Then, PCA is applied to them in order to reduce the number of variables and preserve information. 
The reduced data is tested on 3 different clustering methods (K-Means, K-Medoids, and Gaussian-Mixture-Modeling). The best clustering method was determined by it's Silhouette Score and the profiles given by the clusters. Silhouette Score tells us how distinct clusters in our model are from one another. The cluster profiles were rendered from customer attributes from the unscaled data. A recommendation is presented at the end. 

Read the end of Report.pdf for the results.
