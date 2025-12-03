# ISM-6136_ML-Project
# Predicting Building Energy Efficiency Using Machine Learning
 
This project predicts the **Energy Star Score** of buildings in New York City using machine learning. The score, ranging from 1 to 100, measures a building's energy efficiency and helps city planners, property managers, and building owners make data-driven decisions to reduce energy use and emissions.

---

## Motivation and Business Problem

- Buildings are major energy consumers, impacting costs, carbon emissions, and the environment.  
- Many NYC buildings are old and inefficient.  
- Predicting inefficient buildings enables early interventions, energy audits, and retrofits.  
- The model provides actionable insights for governments, engineers, and property owners.

---

## Data Source

- Data comes from **NYC Local Law 84**, which requires buildings over 50,000 sq. ft. to report annual energy usage.  
- Includes energy use, water consumption, emissions, building characteristics, and Energy Star Scores.

---

## Machine Learning Workflow

1. **Data Cleaning & EDA**  
   - Removed duplicates, fixed column names, and standardized units.  
   - Explored patterns to identify key features.  
   - Handled missing values using median or group averages.  

2. **Feature Engineering**  
   - Created new variables, such as the log of GHG emissions and Site EUI, to reduce the effect of outliers.  
   - Encoded categorical variables for model compatibility.  

3. **Modeling & Evaluation**  
   - Tested multiple models: Linear Regression, SVM, Random Forest, Gradient Boosting, and KNN.  
   - Evaluated models using RMSE (lower values indicate better predictions).  
   - Gradient Boosting performed best and was tuned for optimal performance.  

4. **Interpretation & Recommendations**  
   - Derived actionable insights and business recommendations from model results.

---

## Key Findings

- Older and larger buildings tend to have lower Energy Star Scores.  
- Buildings with high energy intensity (EUI) typically perform worse.  
- Tree-based models, such as Gradient Boosting, capture complex patterns more effectively than linear models.

---

## Business Recommendations

1. **Target Inefficient Buildings**  
   - Prioritize retrofits for buildings with high energy use and low scores.  

2. **Smart Energy Monitoring Tools**  
   - Build dashboards to flag at-risk buildings for early intervention.  

3. **Incentivize Upgrades**  
   - Encourage large commercial and multifamily buildings to improve energy efficiency through financial or policy incentives.

---

## Opportunity in Using Business Analytics

- Predictive analytics allows cities to adopt proactive energy management strategies.  
- Supports urban sustainability, better policy design, and cost savings.  
- Integrates climate goals with financial performance.

---

## Tech Stack

- **Languages:** Python, SQL, R  
- **Libraries & Tools:** Pandas, Scikit-learn, XGBoost, Tableau, Matplotlib  
- **Cloud & Deployment:** Azure  
- **Database:** NYC LL84 dataset

---

## Project Impact

This project demonstrates how **machine learning and business analytics** can help cities and building managers reduce energy consumption, improve sustainability, and plan smarter retrofits.


