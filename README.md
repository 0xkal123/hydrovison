# 🔹 HydroVision: AI-Powered Water Quality Analysis  

## 📌 Overview  
HydroVision is a Machine Learning project that predicts the **potability (drinkability) of water** based on its physicochemical properties.  
The project applies **data preprocessing, exploratory data analysis (EDA), and multiple ML models** to classify water as potable or not.  

This work was done as part of an **Applied Machine Learning (AML) course project (Week 1–3)**.  

---

## 🎯 Project Goals  
- Analyze and preprocess the water potability dataset.  
- Handle missing values, outliers, and class imbalance.  
- Train multiple Machine Learning models.  
- Compare model performance and select the best one.  
- Provide insights into important features affecting water quality.  

---

## 📂 Dataset  
- **Source:** [Kaggle – Water Potability Dataset](https://www.kaggle.com/datasets/adityakadiwal/water-potability)  
- **Size:** 3,276 rows × 10 features  
- **Features:**  
  - pH, Hardness, Solids, Chloramines, Sulfate, Conductivity, Organic Carbon, Trihalomethanes, Turbidity  
- **Target:** Potability (0 = Not Drinkable, 1 = Drinkable)  

---

## ⚙️ Tools & Technologies  
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Imbalanced-learn (SMOTE), XGBoost  
- **Environment:** Google Colab / Jupyter Notebook  
- **Version Control:** GitHub  

---

## 🧪 Methodology  
1. **Data Understanding** – Explore dataset, check summary stats, handle missing values.  
2. **EDA** – Visualize feature distributions, boxplots, heatmaps for correlation.  
3. **Data Transformation** – Imputation, scaling, and class balancing using SMOTE.  
4. **Model Training** – Train Logistic Regression, Random Forest, SVM, XGBoost.  
5. **Model Evaluation** – Accuracy, confusion matrix, classification report.  
6. **Model Comparison** – Identify best-performing model.  

---

## 📊 Results  

| Model                | Accuracy |  
|-----------------------|----------|  
| Logistic Regression  | 50.7%    |  
| SVM                  | 65.0%    |  
| XGBoost              | 68.9%    |  
| **Random Forest**    | **74.6% ✅** |  
| Voting Ensemble      | 71.0%    |  

- **Best Model:** Random Forest  
- **Key Features Influencing Potability:** pH, Sulfate, Solids  

---

## 🚀 Installation & Usage  
Clone the repository and run the Jupyter Notebook:  

```bash
# Clone repo
git clone https://github.com/0xkal123/hydrovison.git

# Navigate into folder
cd hydrovison

# Open the notebook
jupyter notebook HydroVision_Final_Notebook.ipynb
```

Or run in **Google Colab** by uploading the notebook.  

---

## 📁 Repository Structure  
```
hydrovison/
│── water_potability.csv               # Dataset  
│── HydroVision_Final_Notebook.ipynb   # Week 1 + 2 + 3 code  
│── HydroVision_Final_PPT.pptx         # Final Presentation  
│── README.md                          # Project Documentation  
```

---

## ✅ Conclusion  
- HydroVision successfully predicts **water potability using ML**.  
- Random Forest achieved **74.6% accuracy**, the best among all tested models.  
- This project demonstrates how AI can support **sustainable water resource management**.  

---

## 🔮 Future Work  
- Apply hyperparameter tuning for better optimization.  
- Deploy model with Flask/Streamlit web app.  
- Integrate with IoT devices for **real-time water monitoring**.  
- Create dashboards for **community-level decision-making**.  

---

## 👨‍💻 Author  
**[Your Name]**  
AML Course Project – 2025  
