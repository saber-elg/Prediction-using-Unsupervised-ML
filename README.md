# Prediction-Using-Unsupervised-ML

This project demonstrates the use of K-Means clustering, an unsupervised machine learning algorithm, to predict the clustering of the Iris dataset.

## Project Overview

The Iris dataset is a classic and very easy multi-class classification dataset. It contains 150 observations of iris flowers with four features: sepal length, sepal width, petal length, and petal width. The dataset includes three classes: Iris-setosa, Iris-versicolour, and Iris-virginica.

In this project, we use K-Means clustering to classify the iris flowers into three clusters based on their features.

## Requirements

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Project Structure

iris_clustering.py: The main script that performs K-Means clustering on the Iris dataset and visualizes the results.


## Running the Project

Clone the repository:
```sh
Copy code
git clone https://github.com/your-username/Prediction-Using-Unsupervised-ML.git
cd Prediction-Using-Unsupervised-ML
Run the script:
```

Copy code
python main.py
The script will perform the following steps:

- Load the Iris dataset.
- Find the optimal number of clusters using the elbow method.
- Apply K-Means clustering to classify the iris flowers into three clusters.
- Visualize the clusters along with their centroids.
