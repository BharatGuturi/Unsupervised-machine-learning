# unsupervised-machine-learning-challenge
Clustering algorithms to explore whether the patients of a medical research can be placed into distinct groups. 
Exploring the possibility of unsupervised machine learning.
Visualisation to share the findings with the team and other key stakeholders.

# Instructions
1) To execute the project follow the below commands:
   git clone https://github.com/BharatGuturi/unsupervised-machine-learning-challenge.git
2) Install the required libraries using the following commands:
   pip install matplotlib
   pip install pandas 
   pip install plotly
   pip install scikit-learn
3) Run the "Unsupervised Machine Learning.ipynb" file

# Summary
PCA and t-SNE clustering

kmeans analysis


# Conclusion
Using PCA and tsne, the data could not be clustered.
Hence cluster analysis using kmeans was done.The elbow curve between intertia and number of customers could not determine the number of customers where the curve converges.
To obtain a variance ratio of 0.9, number of clusters required were 10.
Using 10 clusters, when the 3dimensional graph was plotted, the clusters could not be identified clearly.
Hence, clustering of the patient's data couldnot be achieved.

