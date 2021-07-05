# Missing Link Prediction

We perform Link Prediction techniques to determine missing links in our graph that will perform prediction for food products to determine whether one food product is similar with the other based on shared ingredients relationships. First, we perform graph loading to load our data from Turtle format into Neo4J. To avoid data leakage, we split our graph into training and test sub graph. Then we will perform feature engineering by measuring common neighbors, preferential attachment, and total neighbors’ score. We also use community detection algorithm like label propagation and Louvain method as additional feature to determine whether node pair is in the same community. We train model using Naive Bayers, KNN, and Random Forest as classifier and perform hyperparameter tuning to ensure maximum performance potential can be reached and perform model evaluation using accuracy, precision, recall, and f1-score as metrics.

## Google Colab

To see the Google Colab version for this codebase: https://colab.research.google.com/drive/1MlqEPszSA4Nz7W_Vs0a-r-js-RrYSWbk?usp=sharing
