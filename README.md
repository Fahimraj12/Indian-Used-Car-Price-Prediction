# Indian-Used-Car-Price-Prediction
Project to predict the price of the used cars in indian metro cities by analyzing the car's features such as company, model, variant, fuel type, quality score and many more.

### Project Abstract:
The aim of this project to predict the price of the used cars in indian metro cities by analyzing the car's features such as company, model, variant, fuel type, quality score and many more.

### Problem Statement:
To develop a reliable machine learning model that accurately predicts the market price of used cars in India based on their features like make, model, age, and kilometers driven. The goal is to provide a data-driven pricing tool for both buyers and sellers to ensure fair and transparent transactions in a volatile market.

### About the Dataset
The "Indian IT Cities Used Car Dataset 2023" is a comprehensive collection of data that offers valuable insights into the used car market across major metro cities in India. This dataset provides a wealth of information on a wide range of used car listings, encompassing details such as car models, variants, pricing, fuel types, dealer locations, warranty information, colors, kilometers driven, body styles, transmission types, ownership history, manufacture dates, model years, dealer names, CNG kit availability, and quality scores.

### Data Dictionary
| Column Name | Description |
| --- | --- |
|ID|Unique ID for each listing|
|Company|Name of the car manufacturer|
|Model|Name of the car model|
|Variant|Name of the car variant|
|Fuel Type|Fuel type of the car|
|Color|Color of the car|
|Killometer|Number of kilometers driven by the car|
|Body Style|Body style of the car|
|Transmission Type|Transmission type of the car|
|Manufacture Date|Manufacture date of the car|
|Model Year|Model year of the car|
|CngKit|Whether the car has a CNG kit or not|
|Price|Price of the car|
|Owner Type|Number of previous owners of the car|
|Dealer State|State in which the car is being sold|
|Dealer Name|Name of the dealer selling the car|
|City|City in which the car is being sold|
|Warranty|Warranty offered by the dealer|
|Quality Score|Quality score of the car|

## Project Workflow

This project follows a structured workflow to ensure a thorough and effective analysis:

1.  **Data Cleaning and Preprocessing:**
    * Handled missing values and removed irrelevant columns.
    * Converted the 'Price' column to a numerical format for analysis.
    * Engineered a new 'Age' feature from the 'Model Year' to represent the car's age.

2.  **Exploratory Data Analysis (EDA):**
    * Visualized the distribution of car features like company, model, fuel type, and color to understand the dataset's composition.
    * Analyzed the relationship between car features and their prices to identify key factors influencing the resale value.
    * Developed an interactive dashboard using Bokeh to allow for dynamic exploration of the data.

3.  **Feature Engineering:**
    * Created new features like 'Brand_Tier' and 'Kms_per_Year' to enhance the model's predictive power.

4.  **Model Building and Evaluation:**
    * Implemented various regression models, including Decision Tree, Random Forest, XGBoost, and LightGBM.
    * Performed hyperparameter tuning using `GridSearchCV` to optimize the models.
    * Evaluated the models using multiple metrics, such as R-squared, MAE, MSE, and RMSE, and employed k-fold cross-validation for robust evaluation.

## Installation

To run this project, you need to have Python and the following libraries installed. You can install them using pip:

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn xgboost lightgbm 


### 👨‍💻 Author
- [Mo Fahim Raj](https://www.linkedin.com/in/mo-fahim-raj-175b9b304/)
- 📧 [mofahimraj@gmail.com]
- 🔗 [GitHub Profile](https://github.com/Fahimraj12)
