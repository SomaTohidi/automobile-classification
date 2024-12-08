# Automobile Dataset Classification Project

## Overview
This project focuses on a classification problem where the goal is to predict the `symboling` column as the target variable. The `symboling` feature represents the insurance risk rating of a car, ranging from -3 (safe) to +3 (risky). Machine learning models are used to classify cars based on this risk rating by leveraging features like engine size, fuel type, price, and more.

### Dataset Description
The dataset contains various features of automobiles, including specifications and pricing details. Below is a summary of the columns:

| Column Name          | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| **symboling**        | Insurance risk rating; ranges from -3 (safe) to +3 (risky).               |
| **normalized-losses**| Normalized average loss payment for each vehicle.                         |
| **make**             | Manufacturer or brand of the car (e.g., Toyota, BMW, Audi).              |
| **fuel-type**        | Type of fuel used; values: 'diesel' or 'gas'.                             |
| **aspiration**       | Type of turbocharger; 'std' (standard) or 'turbo'.                       |
| **num-of-doors**     | Number of doors; 'two' or 'four'.                                         |
| **body-style**       | Body style of the car; e.g., 'sedan', 'hatchback', 'wagon'.               |
| **drive-wheels**     | Drivetrain type; 'fwd' (front-wheel drive), 'rwd' (rear-wheel drive), '4wd' (four-wheel drive). |
| **engine-location**  | Engine placement; 'front' or 'rear'.                                      |
| **wheel-base**       | Distance between the front and rear wheels (inches).                     |
| **length**           | Length of the car (inches).                                               |
| **width**            | Width of the car (inches).                                                |
| **height**           | Height of the car (inches).                                               |
| **curb-weight**      | Weight of the car without passengers and cargo (pounds).                 |
| **engine-type**      | Type of engine; e.g., 'dohc', 'ohcv', 'ohc', 'rotor'.                    |
| **num-of-cylinders** | Number of engine cylinders; e.g., 'four', 'six', 'eight'.                |
| **engine-size**      | Engine displacement (cc).                                                 |
| **fuel-system**      | Fuel delivery system; e.g., 'mpfi', '2bbl', 'idi', '1bbl'.               |
| **bore**             | Cylinder bore diameter (inches).                                          |
| **stroke**           | Piston stroke length (inches).                                            |
| **compression-ratio**| Engine compression ratio.                                                 |
| **horsepower**       | Engine power output (horsepower).                                         |
| **peak-rpm**         | Engine's peak revolutions per minute (rpm).                              |
| **city-mpg**         | Fuel consumption in city driving (miles per gallon).                     |
| **highway-mpg**      | Fuel consumption on highways (miles per gallon).                         |
| **price**            | Price of the car (USD).                                                  |

This detailed description helps in understanding the dataset and serves as the foundation for analysis.

---

## Key Steps
1. **Data Loading**: The data was read from a `.dat` file and column names were standardized.
2. **Data Cleaning**: Missing values were handled, and necessary transformations were applied to prepare the data for modeling.
3. **Exploratory Data Analysis (EDA)**: Statistical insights and visualizations were created to understand the dataset.
4. **Model Training**: Three machine learning models (Logistic Regression, Random Forest, and Neural Network) were trained and evaluated.
5. **Evaluation**: Models were compared using metrics like Precision, Recall, F1-Score, and Accuracy.

---

## Observations
- **Imbalanced Data**: Certain classes, like `symboling`, were underrepresented, impacting model performance.
- **Best Model**: Random Forest with hyperparameter tuning achieved the highest accuracy of 76%.

---

## Future Improvements
1. Address class imbalance using SMOTE or similar techniques.
2. Explore advanced models like Gradient Boosting or XGBoost.
3. Include additional evaluation metrics like ROC-AUC.

---

## Author
- **Name**: Soma Tohidinia
- **Email**: rzss7e@inf.elte.hu
