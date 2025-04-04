# **Facebook Friend Recommendation using Graph-Based Machine Learning**

## **Objective:** 

Predict potential friend connections in a social network using graph-based features and machine learning

## **Graph Construction:** 

Built a directed graph from training data using NetworkX.

## **Feature Engineering:**

Extracted network-based features like PageRank, Jaccard similarity, Adar index, Katz centrality, and Preferential attachment. Applied Singular Value Decomposition (SVD) embeddings for better feature representation.

## **Model Training:**

Used XGBoost classifier for link prediction. Tuned hyperparameters with RandomizedSearchCV for optimal performance.

## **Evaluation**:

Assessed model performance using F1-score, confusion matrix, ROC curve, and AUC score. Identified key features contributing to friend recommendations.

## **Tech Stack:** 

Python, NetworkX, XGBoost, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn.
