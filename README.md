# Customer-Segmentation

This repository contains a Jupyter Notebook that demonstrates the process of customer segmentation using unsupervised clustering. Customer segmentation involves grouping customers into distinct clusters based on their similarities, enabling businesses to better understand and address customer needs.

Table of Contents

Introduction
Dataset
Project Workflow
Technologies Used
Getting Started
Results
Acknowledgements


## Introduction

Customer segmentation is a critical business strategy that helps organizations tailor their products and services to meet diverse customer requirements. In this project, we perform customer segmentation using clustering techniques on a grocery firm's customer dataset.

##Dataset

The dataset used in this project is a customer database from a marketing campaign. It contains features like demographic details, purchasing behavior, and campaign responses.

Source: marketing_campaign.csv (Tab-separated values format)
Size: Approximately 2,240 observations with multiple features.
Contents: Customer demographic information, income, spending habits, and more.

## Project Workflow

Key Steps:

Importing Libraries

  Load essential libraries like pandas, numpy, seaborn, and matplotlib.
Loading Data

  Import the dataset and perform an initial inspection of its structure.
Data Cleaning

  Handle missing values, remove outliers, and standardize features for analysis.
Data Preprocessing

  Encode categorical features and scale numerical data.
Dimensionality Reduction

  Use Principal Component Analysis (PCA) to reduce feature dimensions.
Clustering

  Implement clustering algorithms like KMeans and Agglomerative Clustering.
Evaluation

  Evaluate clusters using metrics such as silhouette score and visualize cluster distributions.
Profiling

  Analyze and interpret the clusters to understand customer segments.

## Technologies Used

Languages: Python
Libraries:

Data Manipulation: pandas, numpy

Visualization: matplotlib, seaborn, mpl_toolkits.mplot3d

Machine Learning: scikit-learn, yellowbrick

## Getting Started

Prerequisites

Python 3.7 or higher

Required Python libraries (install using pip install -r requirements.txt)

Running the Notebook

Clone this repository:
```bash
git clone https://github.com/your-username/customer-segmentation.git
cd customer-segmentation
```

Open the notebook:
```bash
jupyter notebook customer-segmentation.ipynb
```

## Results
The clustering models identified distinct customer groups based on their spending habits, demographics, and campaign responses.
Visualization of the clusters using PCA provided clear insights into the grouping patterns.
