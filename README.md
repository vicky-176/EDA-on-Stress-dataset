# Stress Detection EDA

This project presents a comprehensive Exploratory Data Analysis (EDA) on the Stress Detection dataset. The goal is to identify the key factors, correlations, and behavioral patterns associated with stress. The analysis includes data cleaning, preprocessing, and visualization, offering insights that can support predictive modeling or research in mental health and behavioral science.

## File Included
- **Stress_Dataset.csv** — dataset containing survey responses related to various stress indicators.  
- **EDA on Stress Dataset.ipynb** — Jupyter notebook with all analytical steps and visualizations.

## Dataset Overview
Each record represents an individual’s responses to stress-related survey questions.  
The dataset includes features such as:
- Sleep problems  
- Headaches  
- Irritation  
- Difficulty concentrating  
- Anxiety / tension  
- Rapid heartbeat  

These variables capture physical and psychological symptoms commonly linked to stress levels.

## Structure of the EDA

### 1. Data Cleaning and Preprocessing
- Handled missing values to ensure dataset completeness  
- Simplified lengthy survey question labels into clear, readable column names  
- Verified data consistency and prepared for visualization  

### 2. Univariate Analysis
- Examined distributions of individual stress indicators  
- Used count and distribution plots to understand frequency patterns  

### 3. Bivariate and Correlation Analysis
- Explored relationships between stress indicators  
- Generated correlation heatmaps and pairplots to visualize dependencies  
- Identified feature pairs that commonly co-occur under stress  

## Techniques and Tools
- **Python** for implementation  
- **pandas**, **numpy** for data manipulation and computation  
- **matplotlib**, **seaborn** for visualization and pattern discovery  
- **Jupyter Notebook** for structured analysis and reporting  

## Key Findings
- **Sleep problems** and **headaches** exhibit strong correlation with overall stress.  
- **Irritation** and **difficulty concentrating** often appear together, indicating cognitive strain.  
- **Anxiety** and **rapid heartbeat** are notable physiological markers linked to elevated stress levels.  

## Visualizations Included
- Distribution plots for stress-related variables  
- Correlation heatmap highlighting key relationships  
- Pairwise plots for exploring inter-feature behavior
