# KPMG-1C-project

# AI Studio Challenge Project: Donor Prediction Model

## Project Overview
This project focuses on building a machine learning model to predict donor behavior, specifically the likelihood of donors contributing again in the future. By analyzing past donation data and sociodemographic factors, the model helps identify potential repeat donors.

## Objectives
- Merge donation, demographic, and ZIP code datasets for comprehensive analysis.
- Engineer features and preprocess data to build predictive models.
- Use Random Forest Classifiers for prediction and evaluate the performance.
- Highlight top demographic features influencing donor behavior.

## Methodology
1. **Data Preprocessing**:
   - Merged datasets using ZIP codes and other common attributes.
   - Handled missing values and standardized features.

2. **Feature Engineering**:
   - Extracted donation statistics (e.g., number, average, maximum donations).
   - Selected the top demographic features based on importance.

3. **Model Training**:
   - Metrics: Accuracy, Precision, Recall, F1 Score.
   - Final evaluation on unseen donor data to predict repeat donors

4. **Evaluation**:
   - Random Forest Classifier trained using balanced datasets (Random Oversampling).
   - Stratified K-Fold Cross-Validation for robust evaluation.

## Results
- Top 3 demographic features: `<list derived from script>`
- Model accuracy: `<model accuracy>`
- Predicted repeat donor percentage: `<percentage>`

## Next Steps
- Incorporate more advanced models (e.g., Gradient Boosting).
- Explore additional datasets for deeper insights.
- Fine-tune hyperparameters for optimized performance.

## Installation Instructions
Refer to `Installation` section below.

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo.git
   cd ProjectName
