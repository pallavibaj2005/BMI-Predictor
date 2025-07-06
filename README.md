# Know Your Numbers: Visual and Predictive Analysis of BMI and Health

This project performs an in-depth data analysis and prediction on Body Mass Index (BMI) using user health metrics such as height and weight. It also provides meaningful health suggestions based on the predicted BMI category.

## Project Objective

To build an interactive and visual data analytics project that:
- Analyzes and visualizes BMI trends across individuals
- Recommends health insights and exercise suggestions
- Offers data-driven insights for wellness and awareness
  
## Dataset Description

The dataset includes:
- `Height_cm` — Height of the individual in centimeters  
- `Weight_kg` — Weight of the individual in kilograms  
- `BMI` — Calculated Body Mass Index  
- `Category` — BMI category (Underweight, Normal, Overweight, Obese)

> The BMI is calculated using the formula:
> \[
\text{BMI} = \frac{\text{Weight (kg)}}{\text{Height (m)}^2}
\]


## Key Features

### Exploratory Data Analysis (EDA)
- Scatter plot (BMI vs Weight)
- Histogram of BMI distribution
- Correlation heatmap of features

### Prediction
- Linear Regression used to predict BMI from Height and Weight
- Health suggestions based on BMI category:
  - Ideal weight range
  - Health percentage score
  - Recommended exercises

### Insights
- Understand the impact of weight on BMI
- See how different categories (Obese, Normal, etc.) are distributed
- Explore linear trends between height, weight, and BMI

## ⚙️ Technologies Used

- Python
- Google Colab
- Pandas, NumPy
- Seaborn & Matplotlib (for visualization)
- Scikit-learn (for model training and prediction)

## How to Run

1. Upload the dataset CSV file to Google Colab.
2. Run all cells in the notebook.
3. Enter your height and weight to receive:
   - Predicted BMI
   - BMI Category
   - Health Score
   - Ideal Weight Range
   - Suggested Exercises

