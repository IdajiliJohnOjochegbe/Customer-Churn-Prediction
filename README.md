# Customer-Churn-Prediction
This project aims to predict customer churn using a logistic regression model on a dataset of customer information. The project involves data exploration, preprocessing, feature engineering, and model building.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project demonstrates the use of logistic regression to predict whether a customer will churn based on various features such as demographic data, services subscribed, and account information. The dataset includes information about customer demographics, services they have subscribed to, and whether they have churned.

## Dataset
The dataset used in this project includes the following columns:

- customerID
- gender
- SeniorCitizen
- Partner
- Dependents
- tenure
- PhoneService
- MultipleLines
- InternetService
- OnlineSecurity
- OnlineBackup
- DeviceProtection
- TechSupport
- StreamingTV
- StreamingMovies
- Contract
- PaperlessBilling
- PaymentMethod
- MonthlyCharges
- TotalCharges
- Churn

## Installation
To run this project, you need to have Python and the following libraries installed:

- pandas
- numpy
- scikit-learn
- You can install these dependencies using pip:

bash
```
pip install pandas numpy scikit-learn
```
## Usage
To use this project, follow these steps:

Clone the repository:
bash
```
git clone https://github.com/your_username/customer-churn-prediction.git
```
Navigate to the project directory:
bash
```
cd customer-churn-prediction
```
Run the Jupyter notebook or Python script:
bash
```
jupyter notebook churn_prediction.ipynb
```
or

bash
```
python churn_prediction.py
```
## Results
The logistic regression model achieved the following results:

- Accuracy: 0.82
- Precision: 0.68
- Recall: 0.61
- F1-score: 0.64
These results indicate that the model performs well in predicting customer churn.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or improvements.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
