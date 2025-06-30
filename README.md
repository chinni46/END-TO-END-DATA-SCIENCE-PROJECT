# END-TO-END-DATA-SCIENCE-PROJECT
# Task 3 (Pro Level): End-to-End Data Science Project with Flask Deployment

**Internship**: CODTECH Data Science

---

## 🧠 Objective
To build an end-to-end machine learning pipeline using the Iris dataset and deploy it using a Flask API.

---

## 🛠️ Tech Stack
- Python 3.x
- scikit-learn
- Flask
- joblib

---

## 📁 Files Included
- `Task3_EndToEnd_Project.ipynb` - Notebook with ML pipeline
- `model.pkl` - Trained model file
- `app.py` - Flask app for prediction
- `README.md` - This documentation

---

## ▶️ How to Run

### 1. Install requirements
```bash
pip install flask scikit-learn joblib
```

### 2. Run Flask app
```bash
python app.py
```

### 3. Test the API (use Postman or curl)
```bash
curl -X POST http://127.0.0.1:5000/predict \
     -H "Content-Type: application/json" \
     -d '{"features": [5.1, 3.5, 1.4, 0.2]}'
```

---

## 🔍 API Endpoints
- `GET /` - Welcome route
- `POST /predict` - Accepts JSON `{"features": [..]}` and returns predicted class

---

**Submitted for Completion Certificate**  
**Internship – CODTECH | Task 3**
