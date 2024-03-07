# Flight Fare Prediction Project and Analysis using Power BI

This project focuses on predicting flight fares using machine learning techniques and analyzing the flight dataset using Power BI for valuable insights. The dataset has been meticulously cleaned, transformed, and prepared to ensure optimal performance of predictive models. Various techniques have been applied to enhance accuracy, including the implementation of a Linear Regression model, a Random Forest Regressor, and hyperparameter tuning.

## Data Cleaning and Transformation

The flight dataset underwent comprehensive preprocessing to ensure data quality and suitability for model training:

- **Data Cleaning**: Missing values, duplicates, and irrelevant columns were removed to enhance the integrity of the dataset.
- **Feature Engineering**: New features such as day of the week, month, and time of day were derived from date-time features to capture temporal patterns.
- **Categorical Variable Encoding**: Categorical variables were encoded into numerical format using techniques such as one-hot encoding or label encoding to facilitate model training.
- **Feature Scaling**: Numerical features were scaled to a similar range to prevent bias in model training and to improve convergence speed.

## Models Implemented

### Linear Regression Model

An initial Linear Regression model was deployed to establish a baseline for predicting flight fares. While simplistic, this model provided insights into linear relationships between features and target variables.

### Random Forest Regressor

To further enhance prediction accuracy, a Random Forest Regressor was implemented. This ensemble learning technique harnesses the power of multiple decision trees to capture complex interactions within the data, leading to improved predictive performance.

### Hyperparameter Tuning

Hyperparameter tuning was conducted on the Random Forest Regressor to optimize model performance. Techniques such as grid search or random search were employed to identify the optimal combination of hyperparameters, resulting in a remarkable accuracy of 88.01%.

## Visualization

Visualizations were crafted to elucidate relationships between different features and flight fares. These visualizations aid in identifying patterns, trends, and potential outliers, thereby facilitating informed decision-making during model development and analysis.

## Power BI Dashboard and Analysis

In addition to model building, a dynamic Power BI dashboard was developed to conduct in-depth analysis of the flight dataset:

- **Summary Statistics**: Provides an overview of key metrics such as average fare, route popularity, and distribution of fares.
- **Trend Analysis**: Visualizes fare trends over time, by route, and other relevant factors to identify seasonal variations and market trends.
- **Predictive Analysis**: Integrates predictive models to enable real-time fare predictions, allowing stakeholders to make informed decisions regarding pricing strategies and revenue management.


## Contributors

- [Kashish Kumar Singh](https://github.com/Sniperex)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
