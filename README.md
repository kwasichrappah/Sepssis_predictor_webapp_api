# Sepsis Machine Learning Predictor Project


## Overview
Sepsis is a life-threatening condition that arises when the body's response to an infection causes widespread inflammation. This inflammation can lead to tissue damage, organ failure, and death. Sepsis can result from infections throughout the body, including the lungs, urinary tract, abdomen, and other areas.

Diagnosis: Diagnosing sepsis typically involves a combination of blood tests, imaging tests, and physical examinations to identify the infection source and assess organ function.

Treatment: Treatment often involves antibiotics to fight the infection, intravenous fluids to maintain blood pressure, and other medications to support organ function. In severe cases, patients may require intensive care and support for failing organs, such as mechanical ventilation or dialysis.

## Donor of database: 
                          The Johns Hopkins University
                          Johns Hopkins Road
                          Laurel, MD 20707
                          (301) 953-6231

## Problem Statement
The goal of this project is to develop a machine learning model that can accurately predict which patients are likely to have sepsis by analysing some patient information. By identifying these patients early, the patients can take preventive and precautionary measures to not fall ill and possibly leading to death.

## Dataset
The dataset used for this project contains confidential information about patients in Johns Hopkins University and includes features such as:
- ID 
- PRG (Plasma glucose)
- PL  (Blood Work Result(mu U/ml))         |
- PR Blood Pressure (mm Hg)
- SK Blood Work Result (mm)
- TS Blood Work Result (mu U/ml)                                                                                 
- M11 Body mass index (weight in kg/(height in m)^2)
- BD2 Blood Work Result (mu U/ml)
- Age patients age (years)
- Insurance If a patient holds a valid insurance card
- Sepssis Positive: if a patient in ICU will develop a sepsis , and Negative: otherwise

## Project Structure
- **data/**: Contains the dataset files.
- **sepsis_ml_predictor.ipynb**: Jupyter notebook for data exploration, preprocessing, and model development.`
- **models/**: Saved machine learning tuned models.
- **frontend/**: Web interface for prediction.
- **api/**: Backend (api) service for prediction.
- **dockerfiles**: Dockerfiles to create docker images for version control for all operating systems.
- **README.md**: Project overview and instructions.

## Getting Started
1. Clone the repository:

   #git clone https://github.com/kwasichrappah/Sepssis_predictor_webapp_api

   cd Sepssis_predictor
2. Install dependencies:

   pip install -r requirements.txt

3. Run the Docker container for the web interface and the api

## Dependencies
- Python 3.x
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook
- FastAPI
- Streamlit
- Docker

## Data analysis 
- Data cleaning
- Exploratory data analysis 
- Analytical questions 

## Models
- Logistic Regression
- SVC 
- XGBoost
- CatBoost

## Data balancing / Straification
Data imbalance affects machine learning models by tending only to predict the majority class and ignoring the minority class. The kind of method used is dependent on the datast and what the project tends to achieve. There are a number of methods to take care of that and they include :
- Undersampling
- Oversampling 
- SMOTE

## Model Evaluation
We evaluate the performance of the machine learning models using metrics such as accuracy, precision, recall, and ROC-AUC. Cross-validation and hyperparameter tuning techniques are used to optimize model performance.

## Deployment
The trained machine learning model can be deployed using the scripts provided. This allows real-time prediction of customer churn based on new data.


<!-- AUTHORS -->

## 👥 Authors <a name="authors"></a>

🕵🏽‍♀️ **Emmanuel Chrappah**

-  Github:[Profile](https://github.com/kwasichrappah "Emmanuel Chrappah")
-  Email:[Email](mailto:emmanuel.chrappah@azubiafrica.org?subject=Hi "Hi!")
- Twitter: [Twitter Handle](https://twitter.com/jaychraps)
- LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/emmanuel-chrappah-61115813b/)

🕵🏽‍♀️ **Abigail Amponsah**

-  Email:[Email](mailto:abigail.amponsah@azubiafrica.org?subject=Hi "Hi!")

🕵🏽‍♀️ **Gabriel Kwatei**

-  Email:[Email](mailto:gabriel.kwatei@azubiafrica.org?subject=Hi "Hi!")

##  Contributions 

Contributions, issues, and feature requests are welcome!


## ⭐️ Show your support
If you like this project kindly show some love, give it a 🌟 **STAR** 🌟

## License
This project is licensed under the MIT License - see the LICENSE file for details.





