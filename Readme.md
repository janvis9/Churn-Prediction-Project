1. Project Overview:
This project analyzes customer churn data to identify key factors influencing customer retention. Using Python, we perform Exploratory Data Analysis (EDA), train a Machine Learning model, and visualize important insights.

2. Dataset:
a. The dataset contains customer details, service subscriptions, and whether they churned (left the service) or not.
b. Key features: Tenure, Monthly Charges, Contract Type, Payment Method, Internet Service, etc.
c. Target variable: Churn (Yes/No)

3. Technologies Used:
a. Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
b. Jupyter Notebook / Google Colab
c. Machine Learning Models: Logistic Regression, Random Forest, Decision Trees
d. GitHub (Version Control & Project Hosting)

4. Project Structure
Churn-Prediction-Project/
│── churn_prediction.ipynb      # Jupyter Notebook with EDA & Model Training
│── Churn.csv                   # Dataset
│── README.md                   # Project Documentation

5. Exploratory Data Analysis (EDA)
We analyzed customer churn patterns using visualizations:
Churn Distribution:
Feature Correlation Heatmap:
Feature Importance (ML Model):

6. Installation & Setup
a. Clone the Repository:
git clone https://github.com/janvis9/Churn-Prediction-Project.git
cd Churn-Prediction-Project
b. Install Required Libraries:
pip install pandas numpy matplotlib seaborn scikit-learn
c. Run the Notebook:
Open churn_prediction.ipynb in Jupyter Notebook or Google Colab.
Run the cells step by step to perform EDA, feature engineering, and model training.

7. Key findings
a. Customers with month-to-month contracts have higher churn rates. 
b. Higher monthly charges correlate with increased churn. 
c. Customers using electronic checks tend to churn more. 
d. Random Forest was the best model with an accuracy of `85%

8. How to use this project
a. Run the notebook to explore the data and understand churn patterns.
b. Modify the model and try different algorithms for better accuracy.
c. Use this analysis to develop customer retention strategies. 