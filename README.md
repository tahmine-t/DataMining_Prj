# Data Quality, Preprocessing, and Pattern Extraction Project

This project involves comprehensive analysis, evaluation, and preprocessing of a dataset, followed by pattern extraction, classification, and clustering.

## Project Overview

### Phase 1: Data Understanding and Evaluation

#### Part 1: Understanding the Dataset
1. Feature Analysis:
   - Calculate outliers, median, mode, mean, max, and min for numerical data.
2. Outlier Identification:
   - Use box plots to identify outliers for each feature.

#### Part 2: Data Quality Assessment
1. Quality Evaluation:
   - Assess data quality based on ISO 25012 factors: Consistency, Currentness, Validity, Completeness, Accuracy, and Null values.
2. Error Identification:
   - Identify errors related to Single-Schema, Single-Instance, Multi-Schema, and Multi-Instance issues.
3. Quality Improvement Suggestions:
   - Propose methods to improve data quality.

#### Part 3: Data Preprocessing
1. Handling Missing Values:
   - Impute missing values or remove columns with excessive missing data.
2. Data Conversion:
   - Normalize the data.
3. Feature Engineering:
   - Create new features by combining existing columns.
4. Outlier Treatment:
   - Identify and remove outliers in numerical data.
5. Data Reduction:
   - Apply data reduction techniques if necessary.
6. Categorical Conversion:
   - Convert numerical data to categorical data as needed.
7. Text Data Processing:
   - Perform lemmatization, stemming, and stopwords removal using NLTK.
8. Statistical Comparison:
   - Compare the average rating of sports genre applications with the overall average rating.
9. Data Visualization:
   - Visualize the dataset based on available values.

### Part 4: Combining Datasets
1. Dataset Integration:
   - Integrate the current dataset with a larger dataset by adding missing columns and handling null values.
2. Column Alignment:
   - Match and resolve inconsistencies between similar columns in both datasets.
3. Data Combination for Enhanced Analysis:
   - Combine columns from both datasets for stronger analytical insights and add new columns if beneficial.

### Phase 2: Pattern Extraction, Classification, and Clustering

#### Part 1: Extracting Frequent Patterns
1. Pattern Extraction:
   - Extract at least 7 frequent patterns from the cleaned dataset using mlxtend library.

#### Part 2: Classification & Clustering

1. Clustering:
   - Apply 2 clustering algorithms (K-means and hierarchical algorithms) to segment the dataset.
   - Analyze and review patterns identified within the clusters.
   - Visualize clustering patterns using charts and visualizations.

2. Classification:
   - Feature Selection: Choose relevant features that significantly predict the rating.
   - Model Selection: Test 3 different classification models (e.g., Naive Bayes, Random Forest, Decision Tree, SVM) to find the best performing model.
   - Model Training: Train the selected model using the preprocessed training dataset.
   - Model Evaluation: Evaluate model performance on the test dataset using metrics such as Accuracy, Precision, Recall, and F1-Score.

## Getting Started
1. Clone this repository.
2. Follow the instructions in each phase to understand, evaluate, preprocess, and combine the datasets, as well as to extract patterns, and perform classification and clustering.

## Authors
Tahmine Tavakoli, Elham Armin
