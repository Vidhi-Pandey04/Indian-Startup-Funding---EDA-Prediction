# Indian-Startup-Funding---EDA-Prediction
# Indian Startup Funding Analysis & Prediction (EDA + ML)

This project explores funding trends and investment behaviors in Indian startups using real-world data. We perform detailed Exploratory Data Analysis (EDA), visualize key insights, and build a Machine Learning model to predict the funding amount based on various features like city, sector, and funding type.

---

## Dataset Source

**Data Source:** [Streamlit Startup Dataset](https://github.com/streamlit/streamlit/blob/develop/lib/streamlit/examples/data/startup_funding.csv)  
**Rows:** 2800+  
**Columns:** `date`, `name`, `vertical`, `subvertical`, `city`, `investors`, `type`, `amount`

---

##  Project Highlights

###  Exploratory Data Analysis (EDA)
- Cleaned startup names, investment amounts, and missing investor details.
- Extracted month/year for time-based trend analysis.
- Identified:
  - Top sectors attracting investments.
  - City-wise startup funding volumes (Delhi vs Bengaluru).
  - Top investors and investor networks.
  - Funding rounds like seed, series A, etc.

###  Visualizations
-  Funding trends over time
-  Sector and city-wise distribution
-  Top investors and funding networks
-  Investment type comparisons

###  Machine Learning Model: Predicting Funding Amount
- **Target:** `amount` (converted to float after cleaning)
- **Features:** Encoded versions of city, sector, funding type
- Models tested:
  - Linear Regression
  - XGBoost Regressor
  - Random Forest Regressor
  - **Final Model:**  Ensemble Stacked Regressor

###  Final Model Performance
| Metric              | Value           |
|---------------------|-----------------|
|  Mean Squared Error (MSE) | **6.1**        |
|  R² Score               | **0.3169**       |

 This indicates a well-fitted model considering real-world noise and variance in startup funding data.


---

## Libraries Used

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`
- `xgboost`

---

##  Key Learnings

- Real-world data cleaning, especially with currency and text fields.
- Insightful EDA and storytelling through plots.
- Feature engineering and encoding strategies.
- Model selection, evaluation, and ensemble learning.
- Importance of interpretability and visualization in regression tasks.

---

##  Future Work

- Include external variables like startup age, employee size, or macroeconomic data.
- Time series forecasting of funding trends.
- Build a Streamlit or web-based dashboard to explore funding data interactively.

---

##  Author

**Vidhi Pandey**  
_Data Science Learner | Mathematics Graduate | Python Enthusiast_  
[GitHub](https://github.com/Vidhi-Pandey04)

---

 If you like this project, consider giving it a **star** on GitHub!



