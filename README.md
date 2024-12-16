# Loan Approval Model

## Project Overview
This project demonstrates a loan approval model developed using a **Random Forest classifier**. The model is designed for financial institutions to minimize potential losses from loan defaults by accurately predicting loan approval outcomes.

---

## Key Features
- Utilizes a robust **Random Forest algorithm** to classify loan approval decisions.  
- Achieved high evaluation metrics:  
  - **Accuracy**: 82.28% , 92.87% (Test) 
  - **Precision**: 96.35% (Training), 96.95% (Test)  
  - **Recall**: 71.80% (Training), 69.15% (Test)  
  - **F1-Score**:0.82% (Training) 80.73% (Test)  
- Provides insights into feature importance, with **loan_percent_income** being the most influential predictor.

---

## Technologies Used
- **Python Libraries**:  
  - `pandas`  
  - `scikit-learn`  
  - `matplotlib`  
  - `seaborn`

---

## Installation
1. **Clone this repository**:
   ```bash
   git clone https://github.com/your-username/loan-approval-model.git
   cd loan-approval-model
2. **Install required libraries**  
  pip install -r requirements.txt
## Usage
Run the Jupyter Notebook to explore the model's workflow, including:
- **Data preprocessing**
- **Feature engineering**
- **Model evaluation**

Use the model to predict loan approvals based on new data by providing inputs similar to the dataset.

---

## Key Insights
- The model identifies **loan_percent_income**, **loan_grade**, and **person_income** as critical factors influencing loan approvals.
- High **precision** indicates the model minimizes false approvals, making it ideal for risk-averse institutions.

---

## Future Improvements
- Adjust the model to improve **recall** and inclusivity to capture more positive cases.
- Incorporate additional features or external datasets to enhance prediction accuracy.

---

## Author
**Onyemeziri Valentine Chinazom**  
_Data Scientist and Technical Trainer_  
[LinkedIn Profile](https://www.linkedin.com/in/your-profile)

---

## License
This project is licensed under the **MIT License**.
