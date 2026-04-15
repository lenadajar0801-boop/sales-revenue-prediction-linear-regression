# Sales Revenue Prediction using Linear Regression

## Project Overview

This project focuses on predicting sales revenue using Linear Regression based on advertising budget data.

The model analyzes how different advertising channels (TV, Radio, Newspaper) influence sales and builds a predictive model to estimate revenue.

This project serves as a foundational regression model, demonstrating how linear relationships can be used for business decision-making.

---

## Objective

To build a regression model that predicts sales revenue based on advertising budgets and to understand which channels contribute most to sales.

---

## Dataset

Source: https://www.kaggle.com/datasets/yasserh/advertising-sales-dataset

Dataset Used:

* Advertising.csv

Dataset characteristics:

* Contains 200 records
* Total columns: 5
* Features:

  * TV Ad Budget ($)
  * Radio Ad Budget ($)
  * Newspaper Ad Budget ($)
* Target variable:

  * Sales ($)

---

## Tools & Technologies

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* Jupyter Notebook

---

## Data Preprocessing

### Steps Performed

* Loaded dataset using pandas
* Checked dataset structure using `shape`, `info()`, and `describe()`
* Verified no missing values
* Dropped unnecessary column:

  * Unnamed: 0
* Selected features (X):

  * TV, Radio, Newspaper ad budgets
* Defined target (y):

  * Sales
* Split dataset into training and testing sets (80/20)

### Explanation

The dataset was already clean with no missing values. Removing unnecessary columns and selecting relevant features ensured that the model focuses only on meaningful variables affecting sales.

---

## Model

### Model Used

* Linear Regression

### Steps Performed

* Trained model using training data (160 samples)
* Tested model on unseen data (40 samples)
* Generated predictions
* Evaluated using MAE and R² score

---

## Results

| Metric   | Value     |
| -------- | --------- |
| MAE      | **1.46**  |
| R² Score | **0.899** |

---

## Visualization

### Actual vs Predicted Sales

* Scatter plot comparing actual vs predicted sales
* A diagonal pattern indicates accurate predictions
* Most points align closely, showing strong performance

### Interpretation of Visualization

* Strong alignment → high model accuracy
* Small deviations → minor prediction errors
* Low dispersion → consistent predictions

---

## Interpretation

The Linear Regression model performed well with an R² score of approximately **0.899**, meaning it explains about **89.9% of the variance** in sales.

The Mean Absolute Error of **1.46** indicates that predictions are very close to actual sales values.

---

## Insights

* TV advertising has the strongest influence on sales
* Radio advertising also significantly contributes
* Newspaper advertising has minimal impact
* Sales can be effectively predicted using advertising budgets
* Linear relationships are strong in this dataset

---

## Limitations

* Assumes linear relationships between variables
* Cannot capture complex patterns
* Limited number of features
* External business factors are not included

---

## Future Improvements

* Apply advanced models (Random Forest, Gradient Boosting)
* Add more business-related features
* Perform feature engineering
* Use cross-validation

---

## Conclusion

This project demonstrates how Linear Regression can effectively predict sales revenue using advertising data.

With strong performance (R² ≈ 0.899), the model shows that advertising budgets—especially TV and Radio—play a significant role in driving sales.

This project serves as a strong baseline before applying more advanced machine learning models.

---

## Author

Allen Adajar
Cost Accountant | Data Analyst | Aspiring Data Scientist

GitHub: https://github.com/lenadajar0801-boop
