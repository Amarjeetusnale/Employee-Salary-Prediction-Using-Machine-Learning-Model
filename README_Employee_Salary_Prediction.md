# 💼 Employee Salary Prediction Using Machine Learning

## 📘 Capstone Project  
**Presented By**: Amarjeet Usnale  
**College**: MIT ADT University  
**Department**: BCA in Cloud Computing  

---

## 📋 Table of Contents
1. [Problem Statement](#problem-statement)  
2. [System Development Approach](#system-development-approach)  
3. [Algorithm & Deployment](#algorithm--deployment)  
4. [Result](#result)  
5. [Conclusion](#conclusion)  
6. [Future Scope](#future-scope)  
7. [How to Run the App](#how-to-run-the-app)  
8. [References](#references)  

---

## 🧩 Problem Statement
The goal of this project is to predict whether an employee earns more than $50K or not based on demographic and job-related features.  
- A classification model is trained on census-like data.  
- Features include: age, workclass, education, occupation, etc.  
- A **Streamlit-based web interface** is created for real-time predictions.  
- The system is primarily aimed at assisting HR in decision-making.

---

## 🛠️ System Development Approach
- **Language & Frameworks**: Python 3.9+, Streamlit, Scikit-learn, Pandas  
- **Libraries Used**:  
  - `pandas`  
  - `numpy`  
  - `scikit-learn`  
  - `joblib`  
  - `streamlit`  
- **Methodology**:
  - Data preprocessing using label encoding for categorical variables.  
  - Model training and storage using `joblib`.  
  - Streamlit app for interactive UI and backend integration with the model.

---

## ⚙️ Algorithm & Deployment

1. Load and explore the dataset.  
2. Preprocess the data:
   - Handle missing values  
   - Encode categorical variables using `LabelEncoder`  
3. Split data into training and test sets.  
4. Train classification models such as:
   - `RandomForestClassifier`
   - `GradientBoostingClassifier`  
5. Evaluate using accuracy, precision, and recall.  
6. Save the best performing model using `joblib`.  
7. Build a Streamlit application:
   - Capture user input  
   - Load the trained model and encoders  
   - Predict and display salary category  

---

## 📸 Result
A Streamlit app was developed to demonstrate the prediction interface.

🔗 **GitHub Repository**:  
[Employee Salary Prediction Using Machine Learning Model](https://github.com/Amarjeetusnale/Employee-Salary-Prediction-Using-Machine-Learning-Model)

---

## ✅ Conclusion
- The final model effectively classifies whether an employee earns more than $50K.  
- The web interface is intuitive, making it accessible for HR users without a technical background.  
- Key challenges:
  - Encoding categorical data
  - Hyperparameter tuning

### 🚧 Potential Improvements:
- Transition to salary **regression** for exact amount prediction.  
- **Integration** with real-world HR systems.  
- Implement **Explainable AI** features.  
- Use **database integration** to store predictions.  
- Deploy system on **cloud infrastructure** for scalability.

---

## 🚀 Future Scope (Optional)
- Extend model capabilities for salary range regression  
- Real-time analytics dashboards  
- Cloud-hosted APIs for enterprise integration  

---

## ▶️ How to Run the App

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Amarjeetusnale/Employee-Salary-Prediction-Using-Machine-Learning-Model.git
   cd Employee-Salary-Prediction-Using-Machine-Learning-Model
   ```

2. **Install required libraries**:
   It's recommended to use a virtual environment.
   ```bash
   pip install -r requirements.txt
   ```

   Or manually install:
   ```bash
   pip install pandas numpy scikit-learn joblib streamlit
   ```

3. **Run the Streamlit app**:
   ```bash
   streamlit run app.py
   ```

4. The app will open in your default web browser at:
   ```
   http://localhost:8501
   ```

---

## 📚 References
1. [Kaggle Adult Dataset](https://www.kaggle.com/uciml/adult-census-income)  
2. [Scikit-learn Documentation](https://scikit-learn.org/)  
3. [Streamlit Docs](https://docs.streamlit.io/)  
4. [Python Official Docs](https://docs.python.org/3/)  
5. GitHub repositories, research papers, and online articles related to salary prediction.

---

## 🙏 Thank You!