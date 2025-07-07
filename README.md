# crop-prediction-project
Crop Prediction Using Machine Learning
🔗 [LinkedIn](https://www.linkedin.com/in/madhushaw)


# 🌾 Crop Prediction using Machine Learning

This project aims to predict the most suitable crop to grow based on environmental conditions like temperature, humidity, pH level, and rainfall. It compares multiple machine learning models and evaluates their performance using accuracy, classification reports, and confusion matrices.

---

## 📌 Features

- Predicts best crop based on 7 key features
- Compares 6 ML models:
  - KNN
  - Decision Tree
  - Logistic Regression
  - SVM
  - Naive Bayes
  - Random Forest
- Includes:
  - Accuracy & training time comparison
  - Confusion matrices
  - Feature importance (Random Forest)
- Reusable evaluation function for clean code

---

## 📂 Dataset

- Columns used: `N`, `P`, `K`, `temperature`, `humidity`, `ph`, `rainfall`, `label`
- Dataset Source: [Add source if applicable, e.g., Kaggle or your own CSV]

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 📊 Model Accuracy Summary

| Model               | Accuracy (%) | Training Time (s) |
|---------------------|--------------|-------------------|
| KNN                 | 97.72        | 0.0067            |
| Logistic Regression | 97.27        | 3.43              |
| SVM                 | 97.88        | 0.0386            |
| Naive Bayes         | 99.39        | 0.0078            |
| Decision Tree       | 98.33        | 0.0168            |
| Random Forest       | 99.09        | 0.3858            |

---

## 📌 How to Use

1. Clone the repository  
2. Open the `.ipynb` file in Jupyter or Google Colab  
3. Run all cells to train models and see results  
4. Use your own inputs at the end for crop prediction

---

## 🙋‍♀️ Author

**Madhu Shaw**  
💼 Data Science & Machine Learning Enthusiast  
📍 West Bengal, India

---

## 🌟 Future Work

- Add deep learning-based crop recommendation  
- Integrate real-time weather API for prediction  
- Build a web app using Streamlit or Flask

