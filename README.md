🎓 Student Score Predictor (Machine Learning Project)

This project uses Machine Learning to predict a student's final exam score based on study habits and academic history.

It’s a beginner-friendly regression project built using Python and Scikit-learn.

📌 Project Objective

To build a model that can predict a student’s performance using:

📚 Study Hours

😴 Sleep Hours

🏫 Attendance Percentage

📝 Previous Exam Score

The goal is to understand how different factors influence academic performance.

🧠 Machine Learning Models Used

We trained and compared two regression models:

Linear Regression

Random Forest Regressor 🌲

The model with better performance is saved and can be used for future predictions.

📊 Dataset Information

The dataset contains realistic (synthetic) student performance data.

Feature	Description
study_hours	Number of hours studied per day
sleep_hours	Average sleep hours per night
attendance	Attendance percentage
previous_score	Score from previous exam
final_score	Final exam score (target variable)
⚙️ Technologies Used

Python 🐍

Pandas (Data handling)

Scikit-learn (Machine Learning)

OpenPyXL (Reading Excel files)

🚀 How to Run This Project
1️⃣ Install Required Libraries

Open terminal in the project folder and run:

pip install pandas scikit-learn openpyxl

2️⃣ Train the Model

Run:

python train_model.py


This will:

Train both ML models

Show performance scores

Save the best model as:

student_score_model.pkl

📈 Example Use Case

This type of model can help:

Identify students who may need extra support

Understand the impact of study and sleep habits

Build smarter academic analytics systems

🔮 Future Improvements

Add a Streamlit web app for live predictions

Use a real-world dataset

Try more advanced models (XGBoost, Neural Networks)

Add data visualizations 📊

👩‍💻 Author

Maria Benedict
Aspiring Data Scientist & ML Enthusiast 🚀
