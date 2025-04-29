
# 🔥 Wildfire Detection with Satellite Imagery using AI

A machine learning project using NASA FIRMS MODIS data to detect and analyze wildfire activity across Australia.  
This work supports my master thesis on climate-related AI applications.

---

## 📌 Project Goal

To develop an explainable AI-based pipeline that detects wildfire events using satellite data, analyzes patterns over time and geography, and classifies fire confidence levels to support **disaster response** and **climate resilience**.

---


---

## 🧠 ML Workflow

- **Step 1: Data Loading** – NASA FIRMS MODIS archive (validated fire data)
- **Step 2: Preprocessing** – Converted datetime, handled missing values
- **Step 3: Feature Engineering** – Season, region ID, satellite type, day/night
- **Step 4: EDA & Visuals** – Monthly trends, brightness histograms, fire maps
- **Step 5: Modeling** – Predicting fire `confidence_level` (Low, Medium, High)
- **Step 6: Evaluation** – Classification report + confusion matrix
- **Step 7: Future Work** – Add explainability (SHAP, Grad-CAM)

---

## 📊 Example Visuals

| Monthly Fires | Geo Scatter Map |
|---------------|-----------------|
| ![Monthly Fires](reports/monthly_fires.png) | ![Fire Map](reports/fire_map.png) |

> *(Add these images in `reports/` folder for auto-preview on GitHub)*

---

## 🤖 Models Used

| Model                | F1-Score (High Confidence) |
|---------------------|----------------------------|
| Random Forest        | 0.89                       |
| XGBoost              | 0.88                       |
| Logistic Regression  | 0.77                       |

- High confidence fires detected with **92% recall**
- Low confidence underperformed due to **class imbalance**

---

## 🧪 Tech Stack

- **Python** – Data processing
- **Pandas, NumPy** – EDA & feature engineering
- **Seaborn, Plotly** – Visualization
- **Scikit-learn, XGBoost** – Modeling
- **Jupyter** – Prototyping

---

## 📌 Future Improvements

- Incorporate **SHAP** for explainable outputs
- Add LSTM for **temporal fire forecasting**
- Deploy on Streamlit/Gradio for real-time fire classification

---

## 👩‍💻 Author

**Dilrabo Khidirova** – AI & Data Science Master’s Researcher  




https://www.kaggle.com/code/dilrabonu/australia-bush-fire-staellite-nasa
