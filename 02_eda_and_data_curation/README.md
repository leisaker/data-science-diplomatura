# 02 — Exploratory Data Analysis and Data Curation

## Overview

This folder contains the two practical assignments submitted and approved for the **Exploratory Data Analysis and Data Curation** course.  
The projects focus on the tools, techniques, and workflows required to query, clean, transform, and prepare data for analysis and modeling, with an introduction to concepts from the modern data stack.

The work emphasizes building reliable data preparation pipelines, performing structured exploratory analysis, and preparing datasets suitable for downstream analytical and modeling tasks.

## Skills and Topics Covered

### 🗄️ Data Querying and Manipulation
- SQL fundamentals and practical querying workflows  
- Data manipulation and analysis with pandas  
- Hands-on notebooks for data exploration and inspection  

### 🔧 Data Ingestion and Transformation
- ETL / ELT data ingestion mechanisms  
- Handling missing data and data quality issues  
- Identifying and understanding bias in datasets  
- Data encodings and feature representations  
- Principal Component Analysis (PCA)  
- Common transformations for preparing and enriching datasets  

### 🏗️ Data Modeling
- Layered data modeling approach (raw → cleaned → transformed → analytical layers)  
- Structuring datasets for reproducible and scalable analysis  

### 🚀 Modern Data Stack
- Overview of contemporary tools, concepts, and architectures  
- Introduction to modern data engineering and analytics workflows  

## Tools & Techniques

- Python (pandas, numpy)  
- SQL  
- Jupyter Notebooks  
- Data cleaning, transformation, and preparation workflows  

## Contents

This folder includes two complete practical assignments developed as part of the course:

- **Practical 1 — Data Ingestion, Cleaning, and Curation for Property Price Data:**  
  Built a SQLite database using SQLAlchemy and ingested two datasets: a preprocessed dataset for property price estimation in Melbourne and a dataset with Airbnb prices by zipcode. Validated column types before ingestion and implemented SQL queries for data inspection. Using pandas, selected and justified relevant features for property price prediction, analyzed missing values, explored variable distributions, identified and removed outliers, and visualized their impact. Enriched the dataset by aggregating Airbnb information (e.g., median prices) at the zipcode level, joined both datasets, discussed additional variables and potential use of geospatial information, and finally created and saved a curated dataset with all applied transformations.

- **Practical 2 — Feature Encoding, Imputation, and Dimensionality Reduction:**  
  Applied one-hot encoding to categorical variables to build a fully numerical feature matrix, combined it with numerical features, and performed missing value imputation using an IterativeImputer with a KNN regressor. Compared variable distributions before and after imputation, and discussed the need for feature scaling. Then applied PCA for dimensionality reduction, analyzed the first principal components, added selected components as new features, and exported the final processed dataset. The workflow was documented in a written report describing data selection criteria, transformations, and PCA interpretation.
