# AI-BASED-RECOMMENDATION-SYSTEM

COMPANY: CODTECH IT SOLUTION

NAME: PREETHI ROJA G

INTERN ID: CT04DH1206

DOMAIN: JAVA PROGRAMMING

DURATION: 4 WEEKS

MENTOR: NEELA SANTHOSH

# TASK DESCRIPTION

This Java program implements a User-Based Collaborative Filtering Recommendation System using the Apache Mahout library. It reads user-item interaction data from a file (dataset.csv), calculates user similarity using the Pearson Correlation method, and generates recommendations for each user.

How It Works:
Data Loading:
Loads the dataset from a CSV file (dataset.csv) using FileDataModel.

User Similarity:
Calculates similarity between users using PearsonCorrelationSimilarity.

Neighborhood Selection:
Selects the 2 most similar users (nearest neighbors) using NearestNUserNeighborhood.

Recommendation Engine:
Builds a GenericUserBasedRecommender with the similarity and neighborhood data.

Recommendation Generation:
For each user in the dataset:
Recommends top 3 items they haven’t rated.
Displays the recommended item IDs and their preference values.

# OUTPUT

