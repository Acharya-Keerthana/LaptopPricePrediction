# Laptop Price Prediction Based on Amazon Product Specifications

This repository presents a predictive modeling project aimed at estimating laptop prices using machine learning techniques. The dataset comprises product specifications sourced from Amazon listings, with features engineered for high-quality regression performance.

---

## Overview

Accurately predicting the market value of laptops requires understanding key technical attributes and their impact on pricing trends. Leveraging Amazon product data, this project applies regression models to forecast laptop prices based on:

- Brand and model identifiers  
- Processor specifications (Intel/AMD series, generation, base speed)  
- RAM capacity and type  
- Storage configuration (SSD/HDD, capacity)  
- GPU details (integrated/dedicated, VRAM)  
- Display specifications (size, resolution, refresh rate)  
- Additional features (Touchscreen, weight, OS, battery life)  

---

## Project Architecture

```text
Laptop-Price-Prediction/
├── data/                   # Raw and cleaned dataset (CSV)
├── notebooks/              # Jupyter notebooks for EDA and modeling
├── src/                    # Python scripts for preprocessing & modeling
├── app/                    # Streamlit application
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation
```

## Technologies & Frameworks

- **Programming Language**: Python 3.10+  
- **Libraries**: Pandas, NumPy, Scikit-learn, XGBoost, Seaborn, Matplotlib  
- **Deployment**: Streamlit  
- **Environment Management**: pip / conda  

## Methodology

1. **Exploratory Data Analysis (EDA)**  
   - Pattern identification, distribution plots, correlation analysis  
2. **Data Preprocessing**  
   - Missing value treatment, encoding categorical features, scaling  
3. **Model Development**  
   - Regression algorithms:  
     - Support Vector Regression (SVR)  
     - Random Forest Regressor  
     - XGBoost Regressor  
   - Hyperparameter tuning using GridSearchCV  
4. **Model Evaluation**  
   - Metrics: R² Score, RMSE, MAE  
5. **Web Application**  
   - User-friendly interface via Streamlit  
   - Real-time prediction based on selected inputs  

## Getting Started

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/laptop-price-prediction.git
cd laptop-price-prediction
```

### Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 3: Launch the Application

```bash
streamlit run app.py
```

---

## Key Highlights

- End-to-end pipeline from dataset ingestion to deployment  
- Amazon-style spec interpretation for price insights  
- Model comparison for optimal regression performance  
- Designed for scalability and extension to other product categories  

---

## Future Scope

- Integrate product image analysis using computer vision  
- Deploy to AWS / Azure for broader accessibility  
- Implement feedback loop from real user predictions  


