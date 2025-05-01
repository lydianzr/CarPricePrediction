# CarPricePrediction

## Overview
The project investigates how well different regression models (Random Forest, Linear Regression, and Decision Tree) predict automobile prices based on various features such as the year of manufacture, kilometers driven, fuel type, transmission, and ownership history.

## Key Insights
- The car price distribution is right-skewed, with a majority of cars falling in the lower price range.
- Newer cars tend to command higher prices.
- Lower kilometers driven correlate with higher resale values.
- The dataset consists predominantly of diesel cars, with manual transmissions being more common than automatic.
- Most cars are sold by their first owners.

## Models Evaluated

### 1. **Linear Regression Model:**
   - **Performance:** The linear regression model struggles to predict car prices accurately, as indicated by the substantial disparity between predicted and actual values.
   - **Metrics:** The model performs poorly with high prediction errors, failing to capture complex patterns in the data.

### 2. **Random Forest Regression Model:**
   - **Performance:** The Random Forest model outperforms the Linear Regression model in every evaluation metric.
   - **Metrics:** By utilizing multiple decision trees, the model offers a more nuanced understanding of the relationships in the dataset, yielding accurate predictions.

### 3. **Decision Tree Regression Model:**
   - **Performance:** The Decision Tree model performs reasonably well but doesn’t reach the accuracy of the Random Forest model.
   - **Metrics:** It captures a decent amount of variance in the car prices but has limitations compared to Random Forest.

## Comparison and Conclusion

- The **Random Forest Regression** model demonstrates superior performance in predicting car prices compared to **Linear Regression** and **Decision Tree Regression**. It effectively handles the complexities in the data, delivering better prediction accuracy.
- **Linear Regression** fails to capture the intricate patterns in the dataset, resulting in significant prediction errors.
- **Decision Tree Regression** provides a reasonable prediction but is outperformed by Random Forest.

### Final Conclusion:
When it comes to predicting car prices accurately, **Random Forest Regression** is the preferred model. The results emphasize the need for advanced models that can handle the complexity of automobile pricing datasets. Ongoing research, feature engineering, and model refinement are essential for improving accuracy and adapting to market changes.

## Getting Started

1. Clone this repository.
2. Install necessary libraries by running:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the project in your preferred IDE.
4. Follow the setup instructions in the documentation folder to start contributing.

## Tech Stack

- Python
- Libraries: NumPy, Pandas, Seaborn, Matplotlib, scikit-learn, XGBoost
- Dataset: Provided dataset for car prices and features

## License

This project is for academic purposes.

