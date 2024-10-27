### AI/ML Heart_Failure_Prediction


## Project Overview
This project aims to predict the likelihood of heart failure based on the heart failure records dataset. Using logistic regression, we classify patients as high or low risk for heart failure. The analysis includes exploring feature correlations and visualizing data distributions to gain insights into the dataset.

## Dataset Description
The dataset, `heart_failure_records_dataset.csv`, contains clinical data on heart failure patients. Key features include:

- **SEX**: Gender of the patient (Male = 1, Female = 0)
- **AGE**: Age of the patient
- **DIABETES**: Diabetes status (No = 0, Yes = 1)
- **ANAEMIA**: Anaemia status (No = 0, Yes = 1)
- **HIGH_BLOOD_PRESSURE**: Blood pressure status (No = 0, Yes = 1)
- **SMOKING**: Smoking status (No = 0, Yes = 1)
- **DEATH_EVENT**: Heart failure outcome (No = 0, Yes = 1)

## Project Structure
1. **Exploratory Data Analysis**: Analysis of key features and their distribution, including visualizations of diabetes and death event distribution.
2. **Model Training**: Logistic Regression model for binary classification of heart failure.
3. **Model Evaluation**: Performance assessment using accuracy score and a confusion matrix.

## Requirements
Run the project in a Jupyter Notebook environment with the following libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `plotly`
- `scikit-learn`
- `mlxtend`

Install the required libraries with:
```bash
pip install ----> pandas, numpy, matplotlib, seaborn, plotly, scikit-learn, mlxtend



// Exploratory Data Analysis (EDA)
* Diabetes Analysis: Pie chart showing the proportion of patients with and without diabetes.
* Death Event Analysis: Pie chart showing the relationship between diabetes status and death events.
* Correlation Heatmap: Heatmap to visualize feature correlations, helping identify factors with higher association with heart failure.

// Model Training and Evaluation
*Feature Selection: Key features selected for training: time, ejection_fraction, and serum_creatinine.
*Data Splitting: Dataset split into training and testing sets in an 80-20 ratio.
*Model Selection: Logistic Regression is used to classify patients as high or low risk for heart failure.

// Evaluation Metrics
*Accuracy Score: Printed as a percentage to evaluate model performance.
*Confusion Matrix: Visual representation of actual vs. predicted outcomes.

// Running the Project
*Clone this repository and navigate to the project directory.
*Ensure heart_failure_records_dataset.csv is in the directory.
*Open the Jupyter Notebook and run the cells sequentially.






This `README.md` provides a clear overview of your project, including dataset details, analysis steps, model selection, and potential improvements. Let me know if you like further customization!




################### Author ---> Mohamed Najeeb Ahamed Ash Sharaque Software Engineer [OUSL] ##################

########################################### All Rights Reserved ###############################################
 
