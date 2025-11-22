# Logistic Regression: Predicting Ad Clicks

## Project Overview
This project focuses on predicting whether a user will **click on an online advertisement** using Logistic Regression. Using logistic regression, I built a binary classification model that analyzes user behavior and demographics to forecast ad engagement. This type of predictive modeling helps marketing teams optimize ad targeting strategies and reduce wasted advertising spend.

## Dataset & Key Features
The model uses a mix of demographic and behavioral data, including:

- **Daily Time Spent on Site**
- **Daily Internet Usage**
- **Age**
- **Area Income** 
- **Male** (binary feature)
- **Country** (categorical)
- **City** (categorical)
- **Ad Topic Line** (categorical)
- **Clicked on Ad** (Target: 0 or 1)
The categorical features (Country, City, Topic Line) required transformation before modeling.

## Workflow & Methodology
### 1. Data Cleaning & Preparation
- Conducted initial data assessment using .info() and .describe() 
- Created visualizations to understand feature distributions and relationships
- Split data into **training** and **testing** sets to evaluate model performance effectively.
  
### 2. Model Training
- Trained a **Logistic Regression model** using Scikit-Learn.
- Used scaled and encoded features to accurately map user behavior to the likelihood of clicking an ad.

### 3. Model Evaluation
The model performed strongly, achieving:

- **Accuracy:** about 0.91  
- **Precision:** about 0.91  
- **Recall:** about 0.91  

Evaluation methods included:
- **Classification Report**
- **Confusion Matrix**
- **Accuracy Score**

These metrics showed that the model was reliable at identifying both users who clicked and those who did not.

## Key Insights
- Logistic Regression effectively captured the relationship between user behavior and ad engagement.
- High accuracy and precision mean the model can help marketers:
  - Avoid serving ads to users unlikely to click.
  - Target users with a high probability of conversion.
- Feature engineering for categorical variables played a major role in model performance.
- 
## Techniques & Tools Used
- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-Learn**
- **Logistic Regression**
- **Train/Test Split**
- **Classification Metrics**

## File Included
- **02-Logistic Regression Project.ipynb** — Full notebook with data loading, feature engineering, model training, and evaluation.
- **advertising.csv**
- **README.md**

## How to Run
Clone the repository and launch the notebook using Jupyter:

```bash
jupyter notebook 02-Logistic-Regression-Project.ipynb
```
## Author
Jameela Al-Smadi
jameelasmadi98@gmail.com


