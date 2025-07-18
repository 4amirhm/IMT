1.Introduction

# 🧮 Medical_Insurance

A machine learning project to predict insurance expenses based on demographic and health-related attributes using regression models.

---

## 📌 Project Features

- 📊 Exploratory Data Analysis (EDA)
- ⚙️ Feature Engineering & Preprocessing
- 🧠 Regression Modeling (Linear, Random Forest, XGBoost)
- 📈 Model Evaluation (R², RMSE)
- 💾 Model Saving & Loading

---

## 📂 Project Structure

Medical_Insurance/
│
├── data/ # Input CSV data
├── models/ # Saved trained model
├── notebooks/
│ └── eda.ipynb # Data exploration
├── scripts/
│ ├── preprocessing.py # Data cleaning & encoding
│ ├── modeling.py # Model pipeline creation
│ ├── evaluation.py # Metrics & plots
│ └── save_model.py # Model serialization
├── main.py # Training script
├── requirements.txt # Python dependencies
└── README.md # Project overview


---

## 📈 Dataset Columns

- `age`: Age of the policyholder  
- `gender`: Male/Female  
- `bmi`: Body Mass Index  
- `children`: Number of children covered  
- `discount_eligibility`: Yes/No  
- `region`: Geographical area  
- `expenses`: Medical insurance cost (target variable)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/SepehrHariri/IMT/2- Medical_Insurance.git
   cd 2- Medical_Insurance

---------------------------------------------------------------------------------------------

2. Install dependencies:

pip install -r requirements.txt

---------------------------------------------------------------------------------------------

3. Place your dataset in the data/ folder (e.g., medical_insurance.csv)

---------------------------------------------------------------------------------------------

4. Run the training pipeline:

python main.py

---------------------------------------------------------------------------------------------

🧪 Model Evaluation Example

XGboost
RMSE: 9.1036 
R² Score: 0.99

📦 Output
Trained model saved to: models/insurance_model.pkl

📌 License
This project is open-source and available under the MIT License.