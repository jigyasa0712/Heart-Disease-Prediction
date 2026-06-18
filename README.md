# ❤️ Heart Disease Prediction using Optimized Random Forest
 📄 **Research Paper Accepted at the NIT Patna Conference 2026**
## 📌 Overview
This project aims to predict the presence of heart disease using Machine Learning techniques on the complete **UCI Heart Disease Dataset (920 records)**. The model leverages data preprocessing, feature engineering, and hyperparameter optimization to achieve robust predictive performance.
## Contributors:
- Archita Agrawal : https://www.linkedin.com/in/archita-agrawal-09b85b292/
- Ritika Mittal : [https://www.linkedin.com/in/ritika-mittal-5454sr/](https://www.linkedin.com/in/ritika-mittal-5454sr)
- Jigyasa Arora : https://www.linkedin.com/in/jigyasa-arora-345b51292/

---

## 🚀 Features
- Data preprocessing and missing value handling
- Feature engineering with clinically relevant interaction features
- Hyperparameter tuning using Grid Search
- 5-Fold Stratified Cross-Validation
- Feature importance analysis for interpretability
- High-performance Random Forest classifier

---

## 📊 Dataset
- **Source:** UCI Heart Disease Dataset
- **Samples:** 920
- **Task:** Binary Classification
- **Target:** Presence or absence of heart disease

---

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Libraries:** Scikit-Learn, Pandas, NumPy, Matplotlib, Seaborn
- **Techniques:** Feature Engineering, Hyperparameter Tuning, Cross-Validation

---

## ⚙️ Workflow

1. Data Cleaning and Preprocessing
2. Feature Engineering
3. Model Training
4. Hyperparameter Optimization
5. Performance Evaluation
6. Feature Importance Analysis

---

## 🤖 Models Evaluated

- Logistic Regression
- Decision Tree
- K-Nearest Neighbors
- Support Vector Machine
- Random Forest

---

## 🔍 Feature Engineering

The following interaction features were created to improve model performance:

- Age × Cholesterol
- Blood Pressure × Cholesterol
- ST Depression × Maximum Heart Rate

---

## 📈 Results

| Metric | Score |
|----------|--------|
| Accuracy | **85.87%** |
| ROC-AUC | **0.9167** |
| Weighted F1-Score | **0.86** |

The optimized Random Forest model achieved the best overall performance among the evaluated classifiers.

---

## 📂 Project Structure

```text
Heart-Disease-Prediction/
│
├── heart_disease_prediction.py
├── result_images/
│   ├── Precision-Recall Curve.png
│   ├── ROC Curve.png
│   ├── FeatureImportanceRF.jpeg
│   └── ...
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation & Usage

Follow these steps to set up and run the project locally:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/jigyasa0712/Heart-Disease-Prediction.git](https://github.com/jigyasa0712/Heart-Disease-Prediction.git)
   cd Heart-Disease-Prediction
   ```

2. Set up a virtual environment (Optional but recommended):

   Windows:
   
    ```bash
    python -m venv venv
    .\venv\Scripts\activate
    ```
  
  
    macOS/Linux:
     
     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```

3. Install the required dependencies:
 
   ```bash
   pip install -r requirements.txt
   ```

4. Run the analysis:
   
   Execute the core prediction pipeline:
   
   ```bash
   python heart_disease_prediction.py
   ```



## 📉 Key Findings

- Feature engineering improved predictive performance.
- Random Forest outperformed baseline models.
- ROC-AUC score of **0.9167** demonstrates excellent classification capability.
- Cross-validation ensured model robustness and minimized overfitting.

---

## 🔮 Future Work

- Deep Learning approaches
- Graph Convolutional Networks (GCNs)
- Deployment using Streamlit or Flask

---

## 🏆 Research Contribution

This work has been **accepted for presentation at the NIT Patna Conference 2026**, highlighting its contribution to Machine Learning applications in healthcare.

---

## 📬 Contact

**Jigyasa Arora**

- GitHub: https://github.com/jigyasa0712/Heart-Disease-Prediction
- LinkedIn: https://www.linkedin.com/in/jigyasa-arora-345b51292/
- Email: jigyasaarora712@gmail.com

---

⭐ If you found this project useful, consider giving it a star!
