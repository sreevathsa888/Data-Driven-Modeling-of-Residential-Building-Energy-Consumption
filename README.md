# 🏠 Data-Driven Modeling of Residential Building Energy Consumption

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

### 🧠 Key Findings:

* Relative Compactness is the most important feature
* Glazing Area significantly impacts Cooling Load
* Surface Area strongly affects Heating Load

---

# 📉 Phase 6: Error Analysis

### Visualizations:

* Residual Plot
* Residual Distribution

### Observations:

* Residuals are randomly distributed
* No significant bias detected
* Model predictions are reliable

---

# 🧠 Phase 7: Neural Network Analysis

* Neural Network trained using MLPRegressor
* Training loss curve plotted

### Observations:

* Loss decreases over iterations
* Model converges effectively
* Captures complex relationships

---

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

**Sreevathsa Oleti**
**Kushal**
**Arnav**

---

# ⭐ If you found this project useful, give it a star!
