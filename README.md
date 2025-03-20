# Predictive Analysis of Toxic Chemical Releases
Analyzing EPA Datasets to Predict Future Toxic Chemical Releases

# Overview
This project focuses on processing and analyzing toxic chemical release data using Python. The workflow involves cleaning and transforming raw datasets, mapping codes to meaningful labels, performing visualizations, and building predictive models to forecast toxic emissions over the next five years.

# Files in This Repository
1. **`data_preprocessing.py`**
    - **Purpose**: Processes raw EPA datasets into a cleaned and structured format.
    - **Features**:
      - Handles missing values and standardizes data.
      - Filters relevant data for prediction modeling.
      - Outputs a processed dataset: processed_data.csv.
2. **`feature_selection.py`**
    - **Purpose**: Identifies the most important features for prediction.
    - **Features**:
      - Uses statistical methods and machine learning techniques.
      - Reduces dimensionality while retaining predictive power.
      - Outputs a refined dataset with selected features.
3. **`predictive_model.ipynb`**
     - **Purpose**: Jupyter Notebook implementing machine learning models.
     - **Features**:
           - Explores various regression models for predicting toxic chemical releases.
           - Evaluates models using metrics such as RMSE and R².
           - Visualizes trends in chemical emissions over time.
4. **`visualization.ipynb`**
    - **Purpose**: Generates insightful visualizations of toxic release trends.
    - **Features**:
          - Plots historical data and future predictions.
          - Explores regional and industry-specific emission trends.
          - Uses libraries like matplotlib and seaborn.
      
## Installation and Requirements

### Prerequisites
- Python 3.x
- Required Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scipy`

## Sample Workflow
1.**`Preprocess raw data`**

  - Clean and standardize EPA toxic release datasets
  - Filter out irrelevant features
  
2.**`Feature selection`**

  - Use statistical tests and ML-based feature selection
  
3.**`Train predictive models`**

  - Test different regression models to forecast emissions
  
4.**`Analyze and visualize results`**

  - Generate graphs to understand trends and make data-driven decisions

## Contributions

This project was collaboratively developed by the following contributors:

Madhumitha Somasundaram
College of Engineering and Applied Science, Boulder, Colorado, USA
Madhumitha.Somasundaram@colorado.edu

Sathish Kumar Prabaharan
College of Engineering and Applied Science, Boulder, Colorado, USA
Sathishkumar.Prabaharan@colorado.edu
