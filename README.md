# Credit-Score-Prediction
# Logistic Regression for Credit Score Prediction

This project applies **Logistic Regression** to classify credit scores as "Good" or "Bad" based on given features. The dataset is uploaded via Google Colab, preprocessed, and then used to train and evaluate the model.

## Features Used
- **Age**
- **Income**
- **Loan Amount**

## Dataset Requirements
The dataset should be in **CSV format** and contain a `CreditScore` column. The script automatically converts credit scores into binary categories:
- `1` (Good Credit) if **CreditScore > 600**
- `0` (Bad Credit) if **CreditScore ≤ 600**

## Installation and Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Open Google Colab and upload the script.
3. Run the script and upload your dataset when prompted.

## Workflow
1. **Upload CSV file** in Google Colab.
2. **Preprocess Data**: Handles missing values and transforms `CreditScore`.
3. **Split Data** into training (80%) and testing (20%) sets.
4. **Standardize Features** using `StandardScaler`.
5. **Train Logistic Regression Model** with `class_weight='balanced'`.
6. **Evaluate Model Performance** using accuracy score.

## Output
The model prints:
- Class distribution (`Good` vs `Bad` credit)
- **Accuracy Score** of the model

## Requirements
Ensure you have the following libraries installed:
```bash
pip install pandas scikit-learn
```

## License
This project is open-source and free to use under the MIT License.

