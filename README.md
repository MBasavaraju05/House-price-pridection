# California Housing Prices Regression

This project predicts the median house value in California using a dataset of housing features. The analysis involves data preprocessing, visualization, and regression model training and evaluation.

## Features

The dataset includes the following features:
- **longitude**
- **latitude**
- **housing_median_age**
- **total_rooms**
- **total_bedrooms**
- **population**
- **households**
- **median_income**
- **ocean_proximity** (categorical)

## Workflow

1. **Data Loading**: Load and inspect the dataset.
2. **Data Cleaning**: Handle missing values by dropping rows.
3. **Visualization**:
   - Distribution of categorical variables (e.g., `ocean_proximity`).
   - Heatmap for feature correlation.
4. **One-Hot Encoding**: Encode categorical variables (e.g., `ocean_proximity`).
5. **Feature Selection**: Use Recursive Feature Elimination (RFE).
6. **Modeling**:
   - Linear Regression
   - Random Forest Regression
   - Hyperparameter tuning using GridSearchCV
7. **Evaluation**: Use metrics such as MAE, MSE, and R² score.

## Dependencies

Install the required libraries using the following command:
```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository and navigate to the project directory.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook to explore the workflow.

## Dataset

Ensure the `housing.csv` file is in the same directory as the notebook for proper execution.

---

**Author**: [M BASAVA RAJU]