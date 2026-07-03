# vortextech-aiml-week2
# 🎓 Vortex Tech AI/ML Internship 2026
## Week 2: Build a Classification Model

**Intern:** Zainab Javed  
**Track:** AI & ML  
**Week:** 2 of 4  

---

## 📌 Objective
Train and evaluate a Machine Learning classification model to predict 
whether a student will Pass or Fail based on their background features.

---

## 📊 Dataset
- **Name:** Students Performance in Exams
- **Source:** Kaggle
- **Rows:** 1000
- **Columns:** 8 (gender, race/ethnicity, parental education,
lunch, test prep course, math/reading/writing scores)
- **Target Variable:** Pass/Fail (1/0) — based on average score ≥ 50

---

## 🤖 Models Used
1. **Logistic Regression**
2. **Decision Tree Classifier**

---

## 📈 Results

| Model | Accuracy | Precision | Recall | F1 Score |
|-------|----------|-----------|--------|----------|
| Logistic Regression | 86% | 86.4% | 99.4% | 92.4% |
| Decision Tree | 85% | 87.8% | 95.9% | 91.7% |

### 🏆 Winner: Logistic Regression (F1 Score: 92.4%)

---

## 🔍 Key Findings
- Logistic Regression outperformed Decision Tree overall
- Very high Recall (99.4%) — model correctly identifies almost all passing students
- Test preparation course completion strongly influences Pass/Fail outcome
- Dataset is slightly imbalanced — more Pass cases than Fail

---

## 💡 Improvement Ideas
- Try Random Forest or SVM for higher accuracy
- Add actual exam scores as direct features
- Collect more data on failing students to balance dataset

---

## 🛠️ Libraries Used
- Python 3.12
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🚀 How to Run
1. Clone this repository
2. Install required libraries:
   pip install pandas scikit-learn matplotlib seaborn jupyter
3. Open Jupyter Notebook:
   jupyter notebook
4. Run aiml_Week2_Beginner.ipynb
