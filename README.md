# 💼 Employee Salary Prediction System

An AI-powered web application that predicts the salary range of an employee based on demographic and work-related features. This project was developed as part of an internship with Edunet Foundation.

---

## 🚀 Project Overview

This system uses a **Random Forest Classifier** trained on the `adult.csv` dataset (modified with logic-based salary bands) to predict the salary range of an individual. It includes data preprocessing, outlier detection, model training, evaluation, and an interactive **Streamlit-based web interface** with smart feedback.

---

## 🔍 Features

- 🧠 Predicts salary range based on user input.
- 📊 Displays a **LeetCode-style percentile** chart to show where the user stands.
- 💡 Suggests personalized improvements (e.g., hours/week, education) to increase salary.
- 📄 Option to **download PDF report** of the result.
- 📈 Cleaned and preprocessed data for accurate modeling.
- 🌐 Hosted locally via **Streamlit + Ngrok** for public sharing.

---

## 🛠️ Technologies Used

### 🔧 Languages & Tools:
- Python 3.11
- Streamlit
- Ngrok (for local hosting)
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn
- Joblib

### 📚 Libraries Explained:
- **pandas**: For data manipulation and cleaning.
- **seaborn / matplotlib**: To visualize distributions and analysis.
- **scikit-learn**: For model training and evaluation.
- **joblib**: For saving and loading the trained model and features.
- **streamlit**: To build the web-based user interface.
- **pyngrok**: To expose the local Streamlit app online.

---

## 📊 Model Used

- **Random Forest Classifier**  
  Chosen for its robustness and ability to handle categorical + numerical features with good accuracy.

---

## 🧩 Project Structure

