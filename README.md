##end to end project
Student Performance Indicator 🎯
An end-to-end Machine Learning project that predicts a student's math score based on demographics, education background, and test preparation.
Built with Flask, trained on real exam performance data, and deployed with a simple web interface.

🚀 Project Overview
Objective: Predict the student's math exam score.

Tech Stack: Python, Flask, HTML/CSS (Bootstrap), Machine Learning (Regression), Scikit-learn.

ML Workflow: Data preprocessing ➡️ Model training ➡️ Model saving ➡️ Web deployment.

📁 Project Structure
bash

├── app.py                  # Flask application
├── src/                     # Source code (Data ingestion, transformation, model training, etc.)
├── templates/               # HTML templates for frontend
├── static/                  # (optional) For CSS/JS if needed later
├── artifacts/               # Trained models and artifacts
├── notebook/                # Jupyter notebooks (EDA, model building)
├── requirements.txt         # Python dependencies
├── setup.py                 # Package setup
└── README.md                # (This file!)


💻 How to Run Locally

Clone the repository:

bash
git clone https://github.com/mayank-vk/Student-performance-indicator.git
cd Student-performance-indicator

Install dependencies:

bash
pip install -r requirements.txt
Train the model (optional if model.pkl already exists):

bash
python src/train_pipeline.py
Run the Flask app:

bash
python app.py
Open your browser and visit:
http://127.0.0.1:5000/


🎯 Features
Select demographic attributes via a user-friendly form.

Input reading and writing scores.

Predict student's math score instantly.

Clean and responsive design (mobile friendly).