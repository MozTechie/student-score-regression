# 🧠 Student Exam Score Prediction (Linear Regression)

This project uses a simple linear regression model to predict students' **writing scores** based on their **math scores** and **reading scores**. The dataset used is from Kaggle: [Student Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams).

## 🎯 Objective

- Predict the **writing score** using math and reading scores as features.
- Evaluate model accuracy using R² Score and RMSE.
- Visualize the relationship between predicted and actual values.

## 📁 Dataset Details

- Features: `math score`, `reading score`
- Target: `writing score`
- Records: 1000 students
- Source: Kaggle

## 🛠️ Tools & Technologies

- Python (Google Colab)
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (Linear Regression)

## 📊 Model Results

- **R² Score:** 0.90
- **Root Mean Squared Error (RMSE):** 4.86
- Strong correlation observed:
  - `reading score` vs `writing score`: 0.95
  - `math score` vs `writing score`: 0.80

## 📈 Visualization

The scatter plot shows how close the predicted scores are to the actual scores, indicating strong model performance for a simple regression.

> 📷 You can include a plot image here by uploading a screenshot and linking it.

## 🔄 How to Use

1. Download the dataset from Kaggle.
2. Run the notebook in Google Colab.
3. Modify or expand the model as needed (e.g., try other regression algorithms).
4. Evaluate and visualize the performance.

## 🚀 Future Improvements

- Try advanced regressors like **Random Forest**, **XGBoost**, or **SVR**
- Add a **classification task** (e.g., pass/fail label)
- Deploy with **Streamlit** or **Flask** for interactive predictions

## 📌 Author

Created as part of a machine learning portfolio project.  
Feel free to fork, improve, or contact me with any feedback!

