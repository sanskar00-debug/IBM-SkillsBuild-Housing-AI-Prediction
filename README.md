# Housing Price Analytics & AI Prediction System

This repository contains the complete project submission for the **IBM SkillsBuild Data Analytics with AI Academic Internship Program**. The system uses a machine learning regression pipeline to predict regional housing values based on historical U.S. Census indicators.

---

## 👥 Student Details
* **Student Name:** Sanskar Dhananjay Muneshwar
* **Domain:** Data Analytics with AI
* **Project Name:** Housing Price Analytics & AI Prediction

---

## 📂 Repository Structure

| File Name | Description |
| :--- | :--- |
| `SanskarDhananjayMuneshwar_HousingPrediction.ipynb` | Main Jupyter Notebook with complete Python code, data exploration, charts, and machine learning model. |
| `SanskarDhananjayMuneshwar_CleanedDataset.csv` | The preprocessed and cleaned California Housing dataset ready for modeling. |
| `SanskarDhananjayMuneshwar_ProjectReport.docx` | Comprehensive 5-page formal project documentation and results analysis. |
| `requirements.txt` | List of Python dependencies required to run the codebase locally. |
| `README.md` | Repository overview, setup instructions, and execution workflows. |

---

## ⚙️ Technical Architecture & Workflow

1. **Exploratory Data Analysis (EDA):** Generates distribution curves, core feature maps, and correlation heatmaps to extract data insights.
2. **Data Preprocessing:** Splitting dataset into training (80%) and testing (20%) matrices followed by scale standardization using `StandardScaler`.
3. **AI Modeling:** Implementing a 100-tree `Random Forest Regressor` ensemble model to handle spatial variables and non-linear interactions.
4. **Performance Evaluation:** Calculating metrics including Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared Accuracy (~80%).

---

## 🚀 Step-by-Step Local Deployment

### 1. Clone or Download the Project
```bash
git clone https://github.com
cd IBM-SkillsBuild-Housing-AI-Prediction
```

### 2. Install Libraries
Install all required framework dependencies using the text configuration file:
```bash
pip install -r requirements.txt
```

### 3. Execution
Launch the notebook interface or run it directly inside a web interface environment like Google Colab to see visual metrics:
```bash
jupyter notebook SanskarDhananjayMuneshwar_HousingPrediction.ipynb
```

---

## 📊 Summary of Model Insights
* **Top Predictive Indicator:** Median block income (`MedInc`) represents the dominant driver behind high real estate values.
* **Geographic Trends:** Coastal proximity and urban population clusters display dramatic price increases compared to inland zones.

---
*Disclaimer: This project was built as part of an official academic internship track under the IBM SkillsBuild platform framework.*
