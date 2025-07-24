# 🌐 Telecom ChurnShield 🚀

_A machine learning-powered solution to predict and prevent customer churn in the telecom industry._

This cutting-edge system provides **data-driven insights** to help telecom providers **retain customers** and **boost revenue** with precision.

---

## 🎯 Mission

Customer churn is a silent killer of telecom business growth. **ChurnShield** leverages advanced machine learning to **predict churn risk**, enabling companies to deploy smart retention strategies and keep their users connected. 📞

---

## 📊 Dataset Overview

### 🧪 Training Data

- **Records:** 4,250
- **Features:** 19 + `churn` (target)
- **Class Distribution:**
  - 🟢 **No Churn:** 3,652 (85.93%)
  - 🔴 **Churn:** 598 (14.07%)
- **Role:** Model training and optimization

### 🔍 Test Data

- **Records:** 750
- **Features:** 19 (excluding target)
- **Role:** Model evaluation on unseen data

---

## 🛠️ Tech Stack

| 🧰 Tool                 | 🎨 Purpose                          |
| ----------------------- | ----------------------------------- |
| **Python**              | Core engine for ML magic            |
| **Pandas, NumPy**       | Data wrangling & preprocessing      |
| **Scikit-learn**        | Model training & evaluation metrics |
| **Matplotlib, Seaborn** | Data visualization                  |
| **Jupyter Notebook**    | Interactive development environment |

---

## 🧠 ML Models Implemented

Four powerful ML algorithms were trained and evaluated:

| 🔍 Model                  | 🎯 Accuracy (%) | 🌟 F1 Score |
| ------------------------- | --------------- | ----------- |
| Naive Bayes (NB)          | 88.5%           | 0.88        |
| Decision Tree (DT)        | **92.5%**       | **0.92**    |
| K-Nearest Neighbors (KNN) | 90.5%           | 0.90        |
| Support Vector Machine    | 90.8%           | 0.91        |

🏆 **Decision Tree** outperformed others with high accuracy and explainability.

---

## ⚙️ Workflow Overview

### 1. 🔧 Data Preprocessing

- Removed outliers and missing values
- Applied one-hot encoding to categorical features
- Scaled numerical data
- Addressed class imbalance for fair learning

### 2. 🏗️ Model Training

- Trained and fine-tuned each model
- Applied **k-fold cross-validation**
- Validated with test data for generalization

### 3. 📈 Prediction & Insights

- Generated churn predictions on new data
- Extracted actionable patterns for retention
- Visualized outcomes for business decisions

---

## 💡 Why ChurnShield Stands Out

- ✅ Mastered **class imbalance** for reliable predictions
- ✅ Compared multiple ML models to choose the best
- ✅ Extracted key **customer insights**
- ✅ Built a **scalable pipeline** for real-world deployment

---

## 🔮 Future Enhancements

- 🔁 Add **ensemble models** (Random Forest, XGBoost)
- ⚖️ Apply **SMOTE** to improve class balance
- 🌐 Deploy with **Flask API** or **Streamlit UI**
- 📊 Connect to **BI dashboards** for real-time insights
- 🧠 Experiment with **deep learning** for complex patterns

---

## 🚀 Get Started

### 📥 Clone the Repository

git clone https://github.com/VikasAmale/CUSTOMER-CHURN-PREDICTION-SYSTEM.git

---

## 🙋‍♂️ Author Information

| Field       | Details                                                          |
| ----------- | ---------------------------------------------------------------- |
| 👨‍💻 Name     | **Vikas Sitaram Amale**                                          |
| 📧 Email    | [vickyamale2004@gmail.com](mailto:vickyamale2004@gmail.com)      |
| 🔗 LinkedIn | [linkedin.com/in/vikasamale](https://linkedin.com/in/vikasamale) |
| 🌐 GitHub   | [github.com/VikasAmale](https://github.com/VikasAmale)           |

---

⭐ Star this repo to support smart, customer-first telecom solutions!
Together, let’s fight churn with code. 💪📉🚀
