# Heart Disease Prediction Project

🧠 Objective
This project aims to develop a machine learning model that can predict the presence or absence of heart disease using medical and lifestyle data. The dataset includes features such as age, cholesterol level, blood pressure, weight, and more.

🛠 Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

📊 Data Preprocessing
- Removed duplicates and handled missing values
- Normalized/standardized data using scaling
- Detected and treated outliers
- Analyzed correlation between features and the target variable (`disease`)

🤖 Models Used
- Logistic Regression
- Random Forest
- Decision Trees

📈 Evaluation Metrics
- Accuracy: 71.12% (Logistic Regression)
- Precision: 72.5%
- Recall: 68.2%
- F1 Score: 70.3%
- Mean Squared Error (MSE): 0.23
- R² Score: 0.1

📌 Key Insights
- Features with the highest impact: **Age**, **Weight**, **Cholesterol**
- Random Forest analysis confirmed **Age** as the most important predictor
- Moderate model performance with potential for improvement using more features or deeper models

📁 Dataset
- `cardio_data.csv`

🔚 Conclusion
This project demonstrates a moderately effective ML model with strong potential for future enhancements. The goal is to assist in early detection of heart disease using key physiological features.
