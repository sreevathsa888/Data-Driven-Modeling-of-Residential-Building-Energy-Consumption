# Data-Driven Modeling of Residential Building Energy Consumption

---

## 📌 Project Overview

This project aims to predict the **energy efficiency of residential buildings** using machine learning techniques. The system estimates:

* 🔥 Heating Load (Y1)
* ❄️ Cooling Load (Y2)

based on building design parameters such as surface area, wall area, glazing area, and orientation.

The project follows a **complete end-to-end data science pipeline**, including data analysis, preprocessing, modeling, evaluation, interpretability, and error analysis.

---

## 🎯 Objectives

* Analyze relationships between building features and energy consumption
* Perform Exploratory Data Analysis (EDA)
* Train and compare multiple machine learning models
* Evaluate model performance using standard metrics
* Identify key features affecting energy consumption
* Provide insights for energy-efficient building design

---

## 📊 Dataset Description

* 📁 Dataset: Energy Efficiency Dataset (ENB2012)
* 📌 Total Samples: 768
* 📌 Features: 8
* 📌 Target Variables: Heating Load (Y1), Cooling Load (Y2)
* ✅ No missing values

### Features:

| Feature              |
| -------------------- |
| Relative Compactness |
| Surface Area         |
| Wall Area            |
| Roof Area            |
| Height               |
| Orientation          |
| Glazing Area         |
| Glazing Distribution |

---

## 🔷 Project Workflow

```
Data → EDA → Preprocessing → Modeling → Evaluation → Feature Importance → Error Analysis → Neural Network Analysis
```

---

# 📘 Phase 1: Exploratory Data Analysis (EDA)

### 🔍 Visualizations:

* Correlation Heatmap
* Feature Distribution Histograms
* Scatter Plots
* Pairplot
* Boxplots

<p align="center">
<img src="https://github.com/user-attachments/assets/6eed59d0-900d-4d68-bcbc-fd8a295faf53" width="750"/>
</p>

---

### 🧠 Key Insights:

* Heating and Cooling loads are strongly correlated
* Surface Area significantly affects energy consumption
* Glazing Area strongly impacts Cooling Load
* Relative Compactness inversely affects energy usage

---

# ⚙️ Phase 2: Data Preprocessing

* Train-Test Split (80% training, 20% testing)
* Feature Scaling using StandardScaler
* Clean and structured dataset

---

# 🤖 Phase 3: Model Training

### Models Implemented:

| Model                           |
| ------------------------------- |
| Linear Regression               |
| Decision Tree                   |
| Random Forest ⭐                 |
| Gradient Boosting               |
| Support Vector Regression (SVR) |
| K-Nearest Neighbors (KNN)       |
| Neural Network (MLP)            |

---

# 📊 Phase 4: Model Evaluation

### Evaluation Metrics:

* R² Score
* RMSE
* MAE

<p align="center">
<img src="https://github.com/user-attachments/assets/9183e66f-8c0f-441f-9ec1-2e293de9d2e2" width="700"/>
</p>

<p align="center">
<img src="https://github.com/user-attachments/assets/bc51f41e-8eeb-4242-ad6f-048ce10d9a06" width="700"/>
</p>

<p align="center">
<img src="https://github.com/user-attachments/assets/0a1887ea-a97f-41eb-9ae3-b43a67055b10" width="700"/>
</p>

<p align="center">
<img src="https://github.com/user-attachments/assets/66b26cac-9f12-4601-9aeb-1b61fc95d55a" width="500"/>
</p>

---

### 📈 Model Performance Table:

| Model             | R²        | RMSE     | MAE      |
| ----------------- | --------- | -------- | -------- |
| Linear Regression | Moderate  | Medium   | Medium   |
| Decision Tree     | High      | Low      | Low      |
| Random Forest     | ⭐ Best    | Lowest   | Lowest   |
| Gradient Boosting | Very High | Very Low | Very Low |
| SVR               | Moderate  | Medium   | Medium   |
| KNN               | Moderate  | Medium   | Medium   |
| Neural Network    | High      | Low      | Low      |

---

### 📊 Visual Outputs:

* R² Comparison Graph
* RMSE Comparison Graph
* MAE Comparison Graph
* Actual vs Predicted Plot

---

# 🔍 Phase 5: Feature Importance (USP 🔥)

### Techniques Used:

| Method                   | Purpose                       |
| ------------------------ | ----------------------------- |
| Random Forest Importance | Feature ranking               |
| SHAP Analysis            | Detailed feature contribution |

<p align="center">
<img src="https://github.com/user-attachments/assets/44e78c62-502b-4e8d-968e-d13775ad4f8e" width="700"/>
</p>

<p align="center">
<img src="https://github.com/user-attachments/assets/e6e0453b-1359-499d-a76d-4a90ac6a32f4" width="700"/>
</p>

---

### 🧠 Key Findings:

* Relative Compactness is the most important feature
* Glazing Area significantly impacts Cooling Load
* Surface Area strongly affects Heating Load

---

# 📉 Phase 6: Error Analysis

### Visualizations:

* Residual Plot
* Residual Distribution

<p align="center">
<img src="https://github.com/user-attachments/assets/b4e7c7ca-b841-4ef9-a3bf-0a79f5835200" width="500"/>
</p>

<p align="center">
<img src="https://github.com/user-attachments/assets/d7c15f48-07d1-4d87-9310-a0f8b6868222" width="500"/>
</p>

---

### Observations:

* Residuals are randomly distributed
* No significant bias detected
* Model predictions are reliable

---

# 🧠 Phase 7: Neural Network Analysis

* Neural Network trained using MLPRegressor
* Training loss curve plotted

<p align="center">
<img src="https://github.com/user-attachments/assets/6f554b24-2a60-415f-94a4-47b4cd3956b1" width="650"/>
</p>

---

### Observations:

* Loss decreases over iterations
* Model converges effectively
* Captures complex relationships

---
# Power BI Dashboard

<img width="650" alt="image" src="https://github.com/user-attachments/assets/35bee3c8-0bcf-4449-9bd7-b366db2d599f" />


<img width="650"  alt="image" src="https://github.com/user-attachments/assets/102efba0-b769-4c88-95fa-68ab12acdb41" />


# 🏆 Final Results

* Random Forest and Gradient Boosting achieved highest accuracy
* Predictions closely match actual values
* Model demonstrates strong generalization

---

# 💡 Unique Contributions

* Multi-model comparison (7 models)
* Feature importance using SHAP
* Neural network integration
* Residual-based error validation
* Complete end-to-end pipeline

---

# 📁 Project Structure

```
Data-Driven-Modeling-of-Residential-Building-Energy-Consumption/
│
├── data/
│   └── energy_efficiency.csv
│
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_Modeling.ipynb
│   ├── 03_Model_Training.ipynb
│   ├── 04_Model_Evaluation.ipynb
│   ├── 05_Feature_Importance.ipynb
│   ├── 06_Error_Analysis.ipynb
│   └── 07_Neural_Network_Analysis.ipynb
│
├── outputs/
│   ├── graphs/
│   ├── models/
│   └── tables/
│
└── README.md
```

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SHAP

---

# 📌 Conclusion

This project demonstrates how machine learning techniques can effectively predict building energy consumption. It provides both accurate predictions and interpretable insights, making it valuable for designing energy-efficient buildings.

---

# 🔮 Future Work

* Apply deep learning models
* Use larger datasets
* Develop real-time prediction systems
* Integrate with smart building technologies

---

# 👨‍💻 Author

**Sreevathsa Oleti**,
**Kushal**,
**Arnav**

---
