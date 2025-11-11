## CVD-Diabetes-Diagnosis App

🩺 Health Risk Assessment Application

This application provides a simulated, rule-based risk assessment for Cardiovascular Disease (CVD) and Type 2 Diabetes based on key physiological and behavioral inputs. Developed as a demonstration for health data analysis, it offers an immediate, dual-diagnosis risk score.

Note: This tool is for educational and demonstrative purposes only and should not be used for actual medical advice.

## ✨ Features

Dual Risk Scoring: Simultaneously calculates risk levels (Low, Moderate, High) for both CVD and Diabetes.
Intuitive Web Interface: Built with a clean, responsive front-end for easy data input and result visualization.
Factor Analysis: Provides clear messaging on the specific input factors (e.g., high BMI, smoking, elevated BP) contributing to the final risk score.
Portable Deployment: Containerized using Docker for reliable, reproducible deployment in any environment.

## 🛠️ Technology Stack

This project leverages Python for backend logic and standard web technologies for the interface.
Backend & Logic: Python 3.11+
scikit-learn: For potential future integration of a trained classification model (currently using a rule-based simulation).
Flask: Web framework and production WSGI server.
Environment Management: venv
Containerization: Docker

##🚀 Installation and Setup

Prerequisites
Python 3.11 or higher
venv (Python virtual environment)
Docker (Optional, but highly recommended for deployment)


## Local Setup
1. Clone the Repository:
```bash
   git[ clone https://github.com/Suhen02/cvd-diabetes-diagnosis_app.git]
   cd disease_risk_pridictor
   ```
2. Create and Activate Virtual Environment:
``` bash
   # On Windows
   python -m venv venv
   .\venv\Scripts\activate

   # On macOS/Linux
   python3 -m venv venv
   source venv/bin/
   ```
3. Install Dependencies:All necessary Python libraries are listed in requirements.txt.  
```bash
   pip install -r requirements.txt
   ```
4. Run the Application (Development):
```bash
   python app.py
   ```   
## 🐳 Docker Deployment (Recommended)
To run the application in a robust, isolated container:
1. Build the Docker Image:
```bash
   docker build -t cvd-diabetes-app
   ```
2. Run the Container:
```bash
   docker run -d -p 8000:8000 --name diagnosis-tool cvd-diabetes-app
   ```   

![Project Banner](https://github.com/Suhen02/cvd-diabetes-diagnosis_app/blob/main/Screenshot%202025-11-12%20010609.png)    