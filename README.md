# 💸**Final Project: Medical Cost Regression Analysis** 

## 📝 Overview
This repository contains the Medical Cost Prediction project, where the objective is to predict medical charges based on various factors such as age, sex, BMI, smoking status, and region. The project includes data preprocessing, feature engineering, and model training using linear regression. Performance is evaluated using metrics like R², MAE, and RMSE.

## 🔍 Project Details
- **Dataset:** Insurance data containing features like age, sex, BMI, smoking status, region, and medical charges.
- **Models Implemented:** Linear Regression.
- **Visualizations:** Histograms, feature vs. charges comparison, and performance metrics for the models.
- **Performance Metrics:** R², MAE, RMSE.
- **Reflections:** Insights and observations documented at each stage of the project.​

## 🚀 Key Results
### 🌟 Pipeline 1 (Linear Regression with Standard Scaling)

- **R²:** 0.78
- **MAE:** 4261
- **RMSE:** 5875

### 🌟 Pipeline 2 (Linear Regression with Polynomial Features and Scaling)

- **R²:** 0.86
- **MAE:** 2923
- **RMSE:** 4694

## 📁 Medical Dataset
- [Insurance dataset from Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance).

## 🔗 Links
- [My GitHub Profile](https://github.com/SchroderJ-pixel)
- [My Classification of Medical Cost Notebook](https://github.com/SchroderJ-pixel/ml-06-medical-cost/blob/main/regression-schroder.ipynb)
- [My Peer Review](https://github.com/SchroderJ-pixel/ml-06-medical-cost/blob/main/peer_review.md)

## 🟢 Setup Instructions
To run this project locally, follow these steps:
1. Clone the repository: 
git clone https://github.com/SchroderJ-pixel/ml-04-mushroom-classification.git
cd ml-04-mushroom-classification

2. Set up a virtual environment (Windows):
python -m venv venv
.\venv\Scripts\activate

3. Install required packages:
pip install -r requirements.txt

4. Launch the Jupyter Notebook:
Navigate to the regression-schroder.ipynb and run all cells to see the results.