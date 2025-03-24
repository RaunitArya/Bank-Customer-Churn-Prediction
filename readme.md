# Customer Churn Prediction

## Objective

The goal of this project is to predict customer churn based on various features such as credit score, account balance, estimated salary, and other demographic factors. The dataset is analyzed using Exploratory Data Analysis (EDA) and a predictive model is built to classify whether a customer will churn or not.

## Dataset

The dataset consists of customer details including:

- **Credit Score**
- **Age**
- **Balance**
- **Estimated Salary**
- **Tenure**
- **Geography**
- **Gender**
- **Number of Products**
- **Has Credit Card**
- **Is Active Member**
- **Exited (Churn Indicator)**

Dataset can be found in Kaggle:

[https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction/code?datasetId=2008274&sortBy=voteCount](https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction/code?datasetId=2008274&amp;sortBy=voteCount)

## Steps to Run the Project

1. **Clone the Repository:**

        git clone https://github.com/yourusername/customer-churn-prediction.gitcd customer-churn-prediction
2. **Create and Activate a Virtual Environment (Optional but Recommended):**

        python -m venv venvsource venv/bin/activate # On macOS/Linuxvenv\Scripts\activate # On Windows
3. **Install Dependencies:**

        pip install -r requirements.txt
4. **Run Jupyter Notebook:**

        jupyter notebook main.ipynb
5. **Perform EDA and Run Model:**

    - Open `main.ipynb`
    - Execute the notebook cells to perform data analysis and train the predictive model.


## Results & Insights

- Various visualizations are generated to understand customer churn patterns.
- Models are trained and evaluated to predict customer churn.
- Recommendations are provided based on insights from EDA.

