# Predicting Customer Purchasing Patterns
The objective of this project is to develop a predictive model that accurately identifies customers who are most likely to book a holiday with British Airways, using historical customer booking data and machine learning techniques.

# Problem Definition

The airline industry is highly competitive, and airlines continuously strive to improve their marketing strategies and drive revenue growth. By accurately predicting which customers are most likely to book a holiday, British Airways can tailor their marketing efforts to target these customers effectively, providing personalized offers and incentives. This project aims to address this critical business problem by developing a predictive model that can accurately predict customer booking behavior.

# Approach

To achieve the goal of predicting customer behavior, this project analyzes various customer data, including travel history and other relevant factors that may influence a customer's decision to book a holiday with British Airways. The predictive model is built using machine learning techniques such as XGBoost, CatBoost, and logistic regression.

The data preprocessing techniques used in this project include robust scaling and ADASYN (Adaptive Synthetic) to handle outliers and imbalances in the data. The performance of the models is compared, and the tuned XGBoost model emerges as the top performer, achieving an accuracy of 91%. The precision and recall metrics for the booking customer class are 95% and 87% respectively.

# Repository Structure

*  `data/`: This directory contains the necessary data files for training and evaluating the predictive model.
*  `notebooks/`: This directory contains Jupyter notebook that demonstrate the data preprocessing steps, model training, and evaluation.
*  `requirements`.txt: This file lists the required Python packages and their versions for running the code in this repository.
*  `README.md`: You are currently reading this file, which provides an overview of the project.

# Getting Started

1. Clone this repository: git clone https://github.com/Asyaahmedd/Predicting-Customer-Purchasing-Patterns.git
2. Install the required packages: `pip install -r requirements.txt`
3. Explore the `notebooks` in the notebooks/ directory to understand the data preprocessing, model training, and evaluation processes.

# Conclusion 

The successful development of a predictive model for customer booking behavior holds great potential for the airline industry, including British Airways. By accurately predicting which customers are most likely to book a holiday, airlines can improve their marketing strategies and enhance customer acquisition and retention efforts.

The insights gained from this project can assist British Airways and other airlines in tailoring their marketing campaigns to target specific customer segments more effectively. By offering personalized offers and incentives to customers who are more likely to book a holiday, airlines can increase customer satisfaction, loyalty, and ultimately drive revenue growth.




