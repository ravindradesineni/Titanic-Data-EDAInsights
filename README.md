# Titanic-Data-EDAInsights
Exploratory Data Analysis (EDA) on the Titanic dataset using Python — uncovering patterns, relationships, and feature insights to support future modeling.
**Objectives:**
- Explore basic data characteristics
- Handle missing values and encode categorical variables
- Normalize numerical features
- Visualize data distributions and correlations
- Remove outliers using IQR method
- Save the cleaned dataset for further use

**Tools & Libraries:**
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Plotly
- Google Colab

**Key Steps:**

1. **Data Exploration**  
   Checked types, missing values, and basic statistics

2. **Data Cleaning**  
   - Filled missing values  
   - Dropped irrelevant columns  
   - Encoded `Sex` and `Embarked`

3. **Feature Scaling**  
   Applied standard scaling to `Age`, `Fare`, `SibSp`, and `Parch`

4. **Outlier Removal**  
   Removed outliers from `Age` and `Fare` using IQR

5. **EDA Visuals**  
   Created histograms, boxplots, correlation heatmap, and bar charts

6. **Dataset Saved**  
   Exported final cleaned dataset as `Titanic_eda_Dataset.csv`

**Output:**
A clean, analysis-ready Titanic dataset for future ML use or deeper insights.
