# HR_analytics_employee_turnover
 
## Project Overview
This project aims to predict employee turnover using ensemble tree-based methods on a synthetically generated dataset inspired by IBM's workforce metrics. The goal is to help organizations identify key factors that influence employee attrition, enabling them to implement strategies to improve retention rates.

## Dataset
The dataset features 35 columns including:

Employee demographics (Age, Gender, MaritalStatus)
Job characteristics (JobRole, JobLevel, Department)
Work environment factors (BusinessTravel, DistanceFromHome, EnvironmentSatisfaction)
Employee satisfaction (JobSatisfaction, RelationshipSatisfaction)
Compensation and work hours (MonthlyIncome, OverTime, StandardHours)


## Tools and Technologies
Python: Primary programming language
Pandas & NumPy: Data manipulation
Seaborn & Plotly: Data visualization
Scikit-Learn: Machine learning models
Jupyter Notebook: Interactive coding environment

### Models Implemented
Random Forest: A robust ensemble method known for its accuracy and ability to rank the importance of features.
Gradient Boosting Machine (GBM): An ensemble technique that builds models sequentially to minimize errors.
Key Metrics
Accuracy: 85%
Precision: 80%
Recall: 78%
F1 Score: 79%
AUC-ROC: 0.88


## Model Training and Evaluation
The models were trained using a split of 70% training data and 30% testing data. Model performance was evaluated based on accuracy, precision, recall, F1 score, and AUC-ROC to ensure robustness and reliability.

## Installation
To run this project, install the required libraries using:

bash
Copy code
pip install -r requirements.txt

## Usage
Execute the Jupyter notebooks to train the models and visualize the results:

bash
Copy code
jupyter notebook Employee_Attrition_Prediction.ipynb
Contributing
Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License
Distributed under the MIT License. See LICENSE for more information.
