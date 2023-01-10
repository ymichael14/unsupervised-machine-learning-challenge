# Unsupervised Machine-Learning Project 

## Let Set the Scene

You are on the data science team of a medical research company that’s interested in finding better ways to predict myopia, or nearsightedness. Your team has tried—and failed—to improve their classification model when training on the whole dataset. However, they believe that there might be distinct groups of patients that would be better to analyze separately. So, your supervisor has asked you to explore this possibility by using unsupervised learning.

You have been provided with raw data, so you’ll first need to process it to fit the machine learning models. You will use several clustering algorithms to explore whether the patients can be placed into distinct groups. Then, you’ll create a visualization to share your findings with your team and other key stakeholders.

## 1. Prepare the Data

We must import/clean the csv turned DataFrame. 

* Import `myopic.csv`
* Removal of the myopic column 
* Standardize datasetgit

![Alt text](/Screenshots/Prepare_Data.png?raw=true "Preparing Data")

## 2. Apply Dimensionalty Reduction

* Perform dimensional reduction with PCA
* Use t-SNE 
* Create scatterpot of t-SNE output
* Are there distinct clusters??

![Alt text](/Screenshots/dim_reduct1.png?raw=true "Dimensional reduction")

![Alt text](/Screenshots/dim_reduct2.png?raw=true "Dimensional reduction")

## 3. Perform Cluster Analysis with K-Means

* Use a for-loop to determine the inertia for each k between 1 to 10
* Determine the elbow of the plot

![Alt text](/Screenshots/Kmeans_cluster.png?raw=true "K-means")

## 4. Recommendation 

The final conclusion the data is giving after running the 3 unsupervised Machine Learning algorithms, the optimal clustering is **3 clusters**.
