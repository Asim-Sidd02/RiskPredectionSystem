# Loan Risk Prediction Model and Report Generation

This repository contains scripts to build a machine learning model for predicting loan risk based on financial data and generate a PDF report with model performance metrics and visualizations.

## Prerequisites

- Python 3.x
- Required Python packages: pandas, scikit-learn, matplotlib, seaborn

Install the dependencies using pip:

```bash
pip install pandas scikit-learn matplotlib seaborn
#Usage
1. Clone the repository
bash
Copy code
git clone https://github.com/your_username/your_repository.git
cd your_repository
2. Prepare your data
Ensure your dataset (german_credit_data.csv) is placed in the root directory of the repository.

3. Build the machine learning model
Script: modelBuilding.py
This script preprocesses the data, trains a Random Forest Classifier, and evaluates its performance.

bash
Copy code
python modelBuilding.py
4. Generate the PDF report
Script: reportGeneration.py
This script generates a PDF report (ML_Model_Report.pdf) containing visualizations and metrics of the trained model.
