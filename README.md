# Customer Segmentation Using K-Means Clustering

## Project Overview
This repository presents a comprehensive analysis of the online retail industry, utilizing a dataset from Kaggle. The dataset includes transactions made between 2010 and 2011. This project focuses on deriving customer insights through segmentation, aiming to optimize marketing efforts and improve overall sales.

## Problem Statement
The goal of this project is to transform raw transaction data into a customer-focused dataset by generating new features. These features will be used to segment customers into different groups using the K-means clustering algorithm. The customer segmentation will provide deeper insights into customer behaviors and preferences, enabling more effective, tailored marketing strategies.

## Project Objectives
The key objectives of this project are outlined below:

- **Data Cleaning & Preprocessing**: Clean the data by addressing missing values, handling duplicates, and removing outliers to ensure smooth clustering processes.
- **Feature Engineering**: Create new, relevant features from the existing data to shift the focus from transactional details to a customer-centric dataset for segmentation.
- **Preprocessing & Scaling**: Apply scaling and dimensionality reduction techniques to optimize the data for clustering algorithms.
- **Customer Segmentation**: Use the K-means clustering algorithm to group customers based on their shopping patterns, supporting personalized marketing efforts.
- **Cluster Profiling & Evaluation**: Analyze the characteristics of each customer segment, and assess the effectiveness of the clusters for marketing initiatives.


### Dataset Description

- **InvoiceNo**: Unique identifier for each transaction. Codes beginning with 'c' signify a canceled transaction.
- **StockCode**: Unique code for each product.
- **Description**: Text description of the product.
- **Quantity**: Number of product units per transaction.
- **InvoiceDate**: Date and time when the transaction occurred.
- **UnitPrice**: Price of a single product unit, in British pounds.
- **CustomerID**: Unique identifier for each customer.
- **Country**: Country associated with the customer.

## Project Files
- **Customer_Segmentation_Using_K-Means_Clustering.ipynb**: The Jupyter notebook containing the project workflow, including data exploration, visualizations, and model implementation.
- **data.csv**: The dataset used for analysis, containing transaction records.
- **README.md**: This file, giving an overview of the project and setup instructions.

## How to Run the Project Locally
To get started with this project locally, follow these steps:

1. **Clone the Repository**: Download the repository to your local machine using the `git clone` command.

2. **Open the Notebook**: Launch the `Customer_Segmentation_Using_K-Means_Clustering.ipynb` notebook using Jupyter Notebook.

3. **Install Dependencies**: Make sure all required Python libraries are installed to ensure smooth execution of the notebook.

4. **Run the Notebook**: Execute all the cells in the notebook to generate results and insights from the analysis.
