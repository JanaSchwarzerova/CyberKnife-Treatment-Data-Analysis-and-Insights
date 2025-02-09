# CyberKnife-Treatment-Data-Analysis-and-Insights

## Overview

This notebook analyzes a dataset of patients who underwent CyberKnife treatment, focusing on understanding how clinical parameters such as age, sex, and diagnoses relate to patient outcomes, including complications and hospitalization duration.

## Steps Covered:

1. **Data Loading**: Import patient data, documents, and diagnoses into a pandas DataFrame for analysis.
2. **Data Preprocessing**: Standardize formats, handle missing data, and calculate age from the date of birth.
3. **Association Rule Mining**: Apply the Apriori algorithm to uncover hidden relationships between different diagnoses codes.
4. **Regression Models**:
   - **Logistic Regression**: Investigate the likelihood of complications based on clinical variables.
   - **Linear Regression**: Predict the length of hospitalization based on patient characteristics.
   - **Random Forest Regressor**: Use an ensemble model to improve prediction accuracy and identify the most important features.
5. **Model Evaluation**: Assess model performance using metrics such as Mean Squared Error (MSE) and R-squared.
6. **Visualization**: Use scatter plots to compare predicted and actual outcomes for better model interpretation.

## Dataset

Our tested dataset consists of three key tables:
- **Patients**: Includes demographic information like patient ID, sex, and date of birth.
- **Documents**: Contains information on documents related to each patient.
- **Diagnoses**: Holds detailed diagnosis codes and related information.

Each of these tables is provided as a CSV file and is loaded into the notebook for further analysis.

## How to Use This Notebook
1. **Upload the Dataset**: Ensure that the dataset files (`patients.csv`, `documents.csv`, `diagnoses.csv`) are uploaded to your Colab environment or linked from a cloud storage service.
2. **Run the Cells Sequentially**: Run each code cell in sequence, starting from data loading to the final evaluation.
3. **Adjust Parameters**: You can modify parameters, such as the minimum support for the Apriori algorithm or the features used in the regression models, to explore different aspects of the data.
4. **Interpret Results**: Review the results of the models and visualizations to understand how clinical factors influence treatment outcomes.

## Prerequisites
- Basic understanding of Python and data science concepts, particularly with libraries such as `pandas`, `matplotlib`, `seaborn`, and `sklearn`.
- The dataset files (`patients.csv`, `documents.csv`, `diagnoses.csv`) must be available for analysis.

## Contact Information
If you have any questions or need further clarifications, feel free to reach out to jana.schwarzerova2@fno.cz
