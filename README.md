# **Predicting Homelessness Rates in California**  
**DATASCI 112 Final Project**

This repository contains our **data analysis, exploration, and machine learning modeling** for predicting homelessness rates across counties in California. We investigate key socioeconomic factors such as **housing costs, political affiliation, racial demographics, and education levels** to build predictive models.

## **Project Structure**
1. **[Pre-processing]** – Data collection, cleaning, and feature engineering.
2. **[Data Exploration]** – Exploratory analysis of homelessness trends.
3. **[Model Predictions]** – Machine learning models to predict homelessness rates.

---

## **1. Data Pre-processing**
**Goal**: Prepare the dataset by **collecting, cleaning, and standardizing data** from multiple sources.

**Datasets Used**:
- **Total Population** (by county)
- **Homelessness Rates** (sheltered & unsheltered)
- **Race Distribution** (White, Hispanic, Black, Asian, Native, Foreign-born)
- **Voter Registration** (Democratic vs. Republican)
- **Education Data** (High school dropout rates)
- **Housing Market Data** (Zillow ZHVI & ZORI Index)

**Techniques**:
- Web scraping & API data collection
- Handling missing values and standardizing column formats
- Merging datasets for analysis

---

## **2. Data Exploration**
 **Goal**: Analyze trends and **identify correlations** between homelessness and socioeconomic factors.

**Key Analyses**:
- **Correlation Matrix** – Identifies relationships between homelessness, political affiliation, education, and race.
- **Geospatial Mapping** – Visualizes high-risk counties for homelessness.
- **Heatmaps & Scatter Plots** – Compares housing costs and homelessness across counties.
- **Voter Registration Trends** – Evaluates political influence on homelessness rates.

**Research Questions**:
- How do housing costs impact homelessness?
- Are there racial disparities in homelessness rates?
- What role does political affiliation play?
- Which counties have the highest homeless populations?

---

## **3. Machine Learning Model Predictions**
**Goal**: Develop predictive models for **homelessness rates using socioeconomic factors**.

**Models Implemented**:
- **Linear Regression** – Establishes baseline predictions.
- **Multiple Regression** – Incorporates multiple predictors for improved accuracy.
- **K-Nearest Neighbors (KNN)** – Uses similarity-based predictions.
- **Random Forest** – Identifies key variables affecting homelessness.
- **XGBoost** – Optimized gradient boosting model for final predictions.

**Model Evaluation**:
- **Mean Absolute Error (MAE) & Root Mean Squared Error (RMSE)**
- **R-squared (R²)**
- **Feature Importance Analysis** to determine top predictors.

**Findings**:
- Housing costs and race distribution were strong predictors.
- Political affiliation showed weak correlation.
- Random Forest and XGBoost outperformed traditional regression models.

---

## **How to Run the Notebooks**
1. Open Google Colab and upload the notebooks.
2. Install dependencies:
   ```bash
   !pip install pandas numpy seaborn scikit-learn xgboost
   ```
3. Run the notebooks sequentially:
   - **Step 1**: Pre-process the data.
   - **Step 2**: Perform exploratory analysis.
   - **Step 3**: Train and evaluate machine learning models.

---

## ** Contributors**
- **Chloe Hughes**
- **David Eduardo Espinoza Sanchez**

**Supervised under DATASCI 112 | Stanford University**
