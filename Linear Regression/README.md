# Linear Regression Project: App vs. Website Strategy
This project tackles a critical business decision for a New York City ecommerce company: Should they prioritize mobile app development or website improvements?

As a consultant, I built a Multiple Linear Regression model to uncover how specific customer behaviors drive yearly spending. The goal wasn't just statistical accuracy—it was translating data insights into clear, actionable strategic direction."
---

## Project Focus: Finding the Leverage Points

Linear Regression was ideal for this analysis because it allowed me to measure how strongly each input feature contributed to customer spending. The coefficients provided meaningful, interpretable signals that guided the final recommendation.
 
### Analytical Approach
Data Features Analyzed
Avg. Session Length: In-store style advice sessions

Time on App: Mobile app usage (minutes)

Time on Website: Website browsing time (minutes)

Length of Membership: How many years the customer has been a member.

Yearly Amount Spent: Target variable
---

## Analytical Workflow

### **1. Data Exploration**  
I began by examining feature distributions and correlations to ensure that a linear model was appropriate for the dataset.

### **2. Feature Engineering**
Splitting data into training and test sets

### **3. Model Training**  
A Multiple Linear Regression model was trained using Scikit-Learn.

### **4. Coefficient Interpretation (The Core Insight)**  
This step formed the backbone of the analysis. Each coefficient was interpreted to quantify how a one-unit increase in its corresponding feature affected yearly spending.

### **. Evaluation**  
Residual analysis was used to verify model assumptions, and standard regression metrics were calculated to assess model performance.

---

## Key Insights & Strategic Recommendations

The Revealing Numbers
The regression coefficients told a compelling story:

Customer Behavior	Impact on Yearly Spending
Length of Membership	+$61.28 per additional year
Time on App	+$38.59 per minute increase
Time on Website	+$0.19 per minute increase
These results pointed to a clear recommendation:

- **Prioritize the mobile app** for future development, as increases in app usage correlate strongly with higher spending.  
- **Invest in customer retention**, since Length of Membership had the strongest overall impact.
---

## Techniques and Metrics

**Modeling:**  
- Multiple Linear Regression (Scikit-Learn)

**Validation:**  
- Train/test splitting  
- Residual diagnostics

**Evaluation Metrics:**  
- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)

---

## File Included

- **02-Linear Regression Project.ipynb**  
  Contains the full workflow, including data exploration, model training, coefficient analysis, and final recommendation.
- **Ecommerce Customers**
- **README.md**  
---

## How to Run

Clone the repository and open the notebook using Jupyter:

```bash
jupyter notebook 02-Linear-Regression-Project.ipynb

