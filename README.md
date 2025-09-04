# 🩺 SymptoScan

SymptoScan is a **machine learning–powered web application** that predicts possible diseases based on user symptoms and medical data.  
It also provides **precautions** and **disease descriptions** to guide users.  


## 🚀 Features

- Symptom-based disease prediction  
- Multiple disease models included:
  - Diabetes  
  - Heart disease  
  - Liver disease  
  - Breast cancer  
  - Lung cancer  
  - Hepatitis  
  - Parkinson’s & more  
- Precaution and description suggestions for predicted diseases  
- Easy-to-use Streamlit web interface  

---

## 🛠 Tech Stack

- **Frontend:** Streamlit (Python-based UI)  
- **Backend / ML Models:** Python, Scikit-learn, XGBoost  
- **Database:** SQLite  
- **Other Tools:** Pandas, NumPy, Joblib  

---

## ✅ Pre-requisites

- Python 3.9+  
- pip (Python package manager)  
- Virtual environment (recommended)  

---

## ⚙ Steps to Run the Project

1. **Clone the repository:**

```
bash
git clone https://github.com/yuvii01/SymptoScan.git
cd SymptoScan-main
```

2. **Create and activate a virtual environment:**

```
python -m venv venv
venv\Scripts\activate    
```

3. **Install required dependencies:**

```
pip install -r requirements.txt
```

4. **Run the Streamlit app:**

```
streamlit run app.py
```

Open your browser and go to:
👉 http://localhost:8501

That’s it — the project should now be running! 🎉

---

## Datasets Used📊

Symptom severity data

Disease descriptions

Precaution lists

Training and testing datasets (Kaggle + public datasets)

---

## Contributing🤝 

Contributions are welcome!
Feel free to fork this repo, raise an issue, or submit a pull request.
