# YourCabs Cancellation Prediction Analysis

## Project Overview
This project focuses on analyzing cab booking data and predicting booking cancellations using Machine Learning classification techniques.

The project involves:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Handling missing values
- Classification model building
- Model comparison and evaluation

The dataset was divided into multiple subsets based on travel types to improve model performance and business understanding.

---

## Problem Statement
Cab booking cancellations can negatively impact operational efficiency and customer experience.

The goal of this project is to:
- Analyze cancellation patterns
- Identify important factors affecting cancellations
- Build predictive models to forecast booking cancellations

---

## Dataset Features
Some important features used in the analysis:

- travel_type_id
- from_area_id
- to_area_id
- package_id
- online_booking
- mobile_site_booking
- booking_created
- vehicle_model_id

---

## Technologies Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Machine Learning Models
- Decision Tree
- Random Forest
- Naive Bayes
  
## Machine Learning Workflow
1. Data Loading
2. Data Cleaning
3. Missing Value Treatment
4. Feature Engineering
5. Label Encoding
6. Data Splitting
7. Model Training
8. Model Evaluation
9. Performance Comparison

## Data Preprocessing
The following preprocessing techniques were applied:
- Dropped unnecessary columns
- Missing value treatment
- Feature transformation
- Encoding categorical variables
- Route-based feature engineering
- Dataset segmentation based on travel type
- 
## Models Implemented

### Decision Tree
Used for classification and interpretable decision-making.

### Random Forest
Used to improve prediction accuracy and reduce overfitting.

## Evaluation Metrics
The models were evaluated using:
- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- 
## Key Insights
- Booking behavior varies across different travel types
- Certain routes show higher cancellation probability
- Feature engineering significantly improved model performance
- Random Forest performed better compared to baseline models

## Future Improvements
- Hyperparameter tuning
- Deployment using Streamlit or Flask
- Real-time cancellation prediction API
- Dashboard visualization using Power BI

## Author
Sonu Kumar
