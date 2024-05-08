# House Value Prediction for Strategic Real Estate Decision Making

This project aims to develop a predictive model to estimate house prices in Ames, Iowa, supporting strategic decision-making for real estate stakeholders. The model leverages machine learning techniques to analyze a wide range of features and provide actionable insights for various groups, including real estate agents, developers, homeowners and buyers.

## Objectives
- Build a predictive model to estimate residential property prices in Ames, Iowa.
- Identify influential features affecting house prices to aid data-driven decision-making.
- Provide targeted recommendations to stakeholders in the real estate industry.

## Dataset
- The dataset, "House Prices of Ames, Iowa," is sourced from Kaggle and contains information on over 1,400 properties and 79 features.

## Project Stages
1. **Business Understanding:** Defines the project objectives and impact for stakeholders.
2. **Data Understanding:** Describes the dataset, its sources, and possible biases.
3. **Exploratory Data Analysis:** Examines key data distributions and correlations.
4. **Data Preparation:** Details data cleaning, feature engineering, and feature selection.
5. **Modeling:**
   - Model Development Strategy
   - Model Implementation: Lasso Regression, Random Forest, XGBoost, SVM, Neural Networks, CatBoost, and Ensemble Methods.
   - Model Selection
6. **Evaluation:** Assesses the best model's performance using RMSE and \(R^2\) scores.
7. **Recommendations and Impact:** Presents targeted recommendations for different stakeholder groups.
8. **Future Work:** Highlights potential areas to improve the model's relevance and accuracy.

## Key Results
- **Best Model:** XGBoost achieved the best performance with an \(R^2\) score of 0.918 and RMSE of 22,326.72.
- **Recommendations:** Provide strategic advice for real estate agents, developers, homeowners, and buyers.

## Repository Contents
- `data/`: Directory containing the datasets.
- `models/`: Directory containing the data understanding, data preparation, and model development scripts.
- `plots/`: Visualizations generated during the analysis.
- `presentation_and_reports/`: Final report and any presentations related to the project.

## How to Use
- Clone the repository to your local environment.
- Explore the notebooks provided for each stage of the project (EDA, data preparation, modeling).
- Modify and run the code to analyze and reproduce the results.
