# Exploratory Data Analysis and Statistical Computations on Telescope Dataset

## Overview

This notebook explores the statistical properties and relationships among attributes in the telescope dataset (`telescope_data.csv`). The dataset contains ten real-valued attributes and a class label which is excluded from this analysis. The focus is on understanding the multivariate mean, covariance matrix, variances, and correlations between attributes. Various computations and visualizations are performed to analyze the dataset comprehensively.

## Data Preprocessing

1. **Loading Data**: The dataset is loaded and cleaned by removing the class label and any missing values.
2. **Preliminaries**: Basic statistics and initial exploration of the dataset.

## Analysis

1. **Multivariate Mean Vector**: Computed to understand the central tendency of each attribute.
2. **Covariance Matrix**:
   - Computed using inner and outer product methods.
   - Provides insights into how attributes vary together.

3. **Attribute Variance**:
   - Identifies the attributes with the largest and smallest variance.

4. **Correlation Analysis**:
   - Computes the cosine similarity between centered attribute vectors.
   - Visualizes scatter plots to explore relationships between selected attributes.

5. **Probability Density Function**:
   - Assumes normal distribution for an attribute and plots its PDF.

6. **Projection Analysis**:
   - Projects two selected attributes onto a specific line and visualizes the projection.

## Results

- **Covariance Analysis**: Attributes `fDist` and `fLength` show the largest positive covariance, indicating a strong linear relationship, while `fConc` and `fConc1` have the smallest covariance.
- **Variance Analysis**: `fDist` has the largest variance, and `fConc1` has the smallest variance.
- **Correlation**: A strong correlation was observed between `fLength` and `fWidth` with a cosine similarity of 0.769.
- **Visualizations**: Scatter plots and density functions provide visual insights into attribute relationships and distributions.
