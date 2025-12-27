# Forest Fire Weather Index (FWI) Prediction System 🔥

An end-to-end Machine Learning web application that predicts the **Forest Fire Weather Index (FWI)** using meteorological parameters.  
The model is built using **Ridge Regression** and deployed using **Flask**.

---

## Live Demo
🔗 (Add your AWS EC2 public URL here after deployment)

---

## Project Overview

Forest fires are influenced by multiple weather and environmental factors.  
This project predicts the **FWI value**, which indicates fire risk severity, based on inputs such as:

- Temperature
- Relative Humidity
- Wind Speed
- Rainfall
- Fire danger indices (FFMC, DMC, ISI)
- Region and Fire Class (binary features)

The application provides a clean UI for user input and returns the predicted FWI score.

---

## Machine Learning Details

- **Model Used:** Ridge Regression  
- **Reason:** Handles multicollinearity well and provides stable predictions  
- **Features:** Numerical + Binary (0/1)  
- **Evaluation Metrics:** MAE, R² Score  

---

## Tech Stack

### Backend
- Python
- Flask

### Machine Learning
- Scikit-learn
- Pandas
- NumPy

### Frontend
- HTML
- CSS (Flask Templates)

### Deployment
- AWS EC2 (Linux)
- GitHub for version control

---

## Project Structure

```text
.
├── app.py
├── model.pkl
├── requirements.txt
├── templates/
│   ├── index.html
│   └── home.html
├── static/
├── README.md
└── .gitignore
