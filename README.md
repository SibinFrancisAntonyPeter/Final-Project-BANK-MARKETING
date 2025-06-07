# PROJECT BANK MARKETING


## Bank Marketing Term Deposit Prediction

This project uses the **Bank Marketing Dataset** from the **UCI Machine Learning Repository** to predict whether a client will subscribe to a term deposit product based on various attributes. The project applies different machine learning models and evaluates their performance.


## Domain

**Marketing / Finance**

---

## Dataset Source

- **UCI Repository:** [Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
- **Instances:** 45,000 records
- **Features:** 16 features + 1 target

---

##  Objective

To predict the likelihood that a customer will subscribe to a term deposit after a direct marketing campaign using classification models.

---

##  Technologies Used

- Python 
- Jupyter Notebook 
- Scikit-learn 
- Pandas / NumPy 
- Matplotlib / Seaborn 

---

##  Features Used

| Feature        | Description                          |
|----------------|--------------------------------------|
| Age            | Customer's age                       |
| Job            | Type of job                          |
| Marital        | Marital status                       |
| Education      | Education level                      |
| Default        | Has credit in default?               |
| Balance        | Average yearly balance               |
| Housing        | Has housing loan?                    |
| Loan           | Has personal loan?                   |
| Contact        | Contact communication type           |
| Day            | Last contact day of the month        |
| Month          | Last contact month of year           |
| Duration       | Last contact duration in seconds     |
| Campaign       | Number of contacts during campaign   |
| Pdays          | Days since last contact              |
| Previous       | Number of contacts before this campaign |
| Poutcome       | Outcome of previous campaign         |
| **Target (y)** | Term deposit subscribed? (yes/no)    |

---

##  Models Applied

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier
- Support Vector Classifier (SVC)

---

##  Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)

---

##  Key Findings

- Feature importance was analyzed.
- Gradient Boosting and Random Forest gave high performance.
- Model tuning was done using hyperparameter optimization.

---

##  Prediction

An unseen customer's data was inserted into the model, and a prediction was made. The model output indicates whether the customer is:
- `Subscribed to term deposit`
- `Not subscribed to term deposit`

---

