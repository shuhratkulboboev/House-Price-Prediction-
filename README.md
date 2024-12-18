# House Price Prediction

This project predicts house prices using machine learning. The following algorithms were implemented:
- Linear Regression
- Decision Tree
- Random Forest

## Dataset
The dataset `DataSet_LakasArak_labeled.csv` contains features and target labels for predicting house prices.
The dataset used is `DataSet_LakasArak_labeled.csv`, which contains features related to properties and their associated house prices.

---

## Dataset Description

The dataset includes various features about properties, such as location, size, and condition. Below is an overview of the dataset:

| **Feature Name**            | **Description**                              | **Missing Values (%)** |
|-----------------------------|----------------------------------------------|-------------------------|
| `county`                   | County where the property is located         | 0.00%                  |
| `city`                     | City of the property                         | 0.71%                  |
| `postcode`                 | Postal code                                  | 36.87%                 |
| `property_type`            | Type of property (e.g., house, apartment)    | 0.00%                  |
| `property_subtype`         | Subtype of the property                      | 2.11%                  |
| `property_condition_type`  | Condition of the property                    | 0.00%                  |
| `property_floor`           | Floor number of the property                 | 4.83%                  |
| `building_floor_count`     | Total floors in the building                 | 53.62%                 |
| `view_type`                | Type of view from the property               | 45.41%                 |
| `orientation`              | Orientation (e.g., North, East, etc.)        | 39.33%                 |
| `garden_access`            | Access to garden (yes/no)                    | 78.10%                 |
| `heating_type`             | Type of heating                              | 14.40%                 |
| `elevator_type`            | Type of elevator (if any)                    | 18.02%                 |
| `room_cnt`                 | Number of rooms                              | 0.00%                  |
| `small_room_cnt`           | Number of smaller rooms                      | 0.00%                  |
| `created_at`               | Date the property listing was created        | 0.00%                  |
| `property_area`            | Total property area in square meters         | 0.00%                  |
| `balcony_area`             | Total balcony area in square meters          | 0.00%                  |
| `price_created_at`         | Date the price was recorded                  | 0.00%                  |
| `ad_view_cnt`              | Number of views on the ad                    | 0.00%                  |
| `active_days`              | Number of days the ad was active             | 0.00%                  |
| `nr`                       | Property ID                                  | 0.00%                  |
| `split`                    | Data split identifier (e.g., train/test)     | 0.00%                  |

---

## Project Overview

### **Objectives**
1. Explore the dataset and clean missing values.
2. Train machine learning models (Linear Regression, Decision Tree, and Random Forest) to predict house prices.
3. Compare model performance using evaluation metrics:
   - R² (coefficient of determination)
   - MAE (Mean Absolute Error)
   - RMSE (Root Mean Squared Error)

### **Steps**
1. **Data Preprocessing**: 
   - Handle missing values.
   - Encode categorical variables.
   - Normalize or scale numerical features (if needed).

2. **Model Training**:
   - Split data into training and testing sets.
   - Train Linear Regression, Decision Tree, and Random Forest models.

3. **Evaluation**:
   - Measure and compare the performance of all models using metrics and visualizations.
   
## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/shuhratkulboboev/House-Price-Prediction-.git
2. Navigate to the repository::
   ```bash
   cd house-price-prediction
3. Navigate to the repository::
   ```bash
   cd house-price-prediction
4. Install dependencies:
   ```bash
   pip install -r requirements.txt

## Results
The models were evaluated using:

R² (coefficient of determination)
MAE (Mean Absolute Error)
RMSE (Root Mean Squared Error)

- Random Forest Regressor outperforms the other models, offering the most accurate predictions.
- Gradient Boosting also performs well, while Linear Regression is the least accurate.
- Ensemble methods (Random Forest, Gradient Boosting) capture more complex data patterns than Linear Regression.




