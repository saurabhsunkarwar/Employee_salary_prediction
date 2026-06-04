💼 Employee Salary Prediction Engine & Flask API

An end-to-end predictive machine learning web application that estimates employee salaries based on professional experience, test scores, and interview performance metrics using **Python**, **Scikit-Learn**, and a **Flask API**.

---

🚀 Architectural Overview
This repository contains a full-stack predictive analytical framework:
1. **Machine Learning Core:** A regression model trained on candidate performance vectors and serialized into a production-ready model artifact (`model.pkl`).
2. **API Deployment Layer:** A lightweight microservice built with **Flask** (`app.py`) that handles incoming POST requests, parses user input fields, and serves real-time inference matrices.
3. **User Interface:** A responsive frontend interface allowing HR professionals or managers to input employee criteria and instantly calculate salary bands.

🛠️ Tech Stack & Dependencies
* **Core Language:** Python 3
* **Machine Learning & Modeling:** Scikit-Learn, Pandas, NumPy
* **Micro-framework API:** Flask
* **Production Configurations:** `Procfile`, `requirements.txt`

📊 Feature Matrix & Inputs
The underlying ML algorithm processes three key quantitative features to evaluate and predict standard salary baselines:
* `Experience`: Total years of relevant professional experience.
* `Test Score`: Quantitative score achieved during technical evaluation phases.
* `Interview Score`: Qualitative evaluation metric from the panel interview loops.

---

⚙️ Local Setup & Execution

Follow these rapid steps to spin up the predictive application locally on your computer:

1. Clone the repository:**
   ```bash
   git clone https://github.com
   cd Employee_salary_prediction
   ```

2. Create and spin up a Python virtual environment:**
   ```bash
   # Windows
   python -m venv venv
   venv\Scripts\activate
   ```

3. Install application dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. Launch the Flask application server:**
   ```bash
   python app.py
   ```
   Open your local browser and navigate to `http://127.0.0` to test the inference engine.

📁 File Structure
```text
├── templates/               # Frontend HTML layout elements
├── app.py                   # Central Flask API server routing logic
├── model.pkl                # Serialized pre-trained regression model
├── requirements.txt         # Package dependency ledger
├── Procfile                 # WSGI web server execution directives
└── README.md                # System documentation
```
