# 🚢 Titanic Survival Prediction

A machine learning project that predicts whether a passenger survived the Titanic disaster based on features such as age, gender, ticket class, and family size.  
This project follows the complete data science workflow — from data cleaning and feature engineering to model building and evaluation.

---

## 📊 Dataset
- **Source**: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic)
- **Training samples**: 891
- **Test samples**: 418
- **Key features**: Passenger Class, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked

---

## 🔍 Project Workflow
1. **Data Loading & Cleaning**
   - Handle missing values in `Age`, `Cabin`, and `Embarked`
   - Remove duplicates (if any)
  
2. **Exploratory Data Analysis (EDA)**
   - Visualize distributions 
   - Identify survival patterns by class, age, gender

3. **Feature Engineering**
   - **Encoding** categorical variables (`Sex`, `Embarked`)
   - **Binning** `Age` into categories
   - **Scaling** numerical features (`Fare`, `Age`)
   - Creating new features: `FamilySize`, `IsAlone`
  
4. **Model Building**
   - Logistic Regression
   - Random Forest Classifier
   - Support Vector Machine (SVM)

5. **Model Evaluation**
   - Accuracy, Precision, Recall
   - Confusion Matrix

---
  
## 🛠 Technologies Used

  - **Pandas**  
  - **NumPy**  
  - **Matplotlib**  
  - **Seaborn**  
  - **scikit-learn**  
  - **Jupyter Notebook**

## 📈 Results
| Model                | Accuracy | Precision | Recall |
|----------------------|----------|-----------|--------|
| Random Forest        | 0.92     | 0.90      | 0.88   |


---

