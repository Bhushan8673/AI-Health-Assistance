# AI Health Assistance

AI Health Assistance is a lightweight health prediction web application that uses machine learning to predict possible diseases based on user-selected symptoms. The project integrates a trained ML model with a Flask backend and a simple HTML frontend.

## Features

- Predicts diseases based on input symptoms
- Integrated Machine Learning model using scikit-learn
- Flask-based web server
- Clean and simple HTML user interface

## Project Structure

- `app.py` – Main Flask application that handles routing and prediction
- `templates/` – Contains the HTML files for the UI
- `static/` – CSS files and other static assets
- `model/` – Trained ML model and dataset files
- `requirements.txt` – List of required Python packages

## Getting Started

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/Bhushan8673/AI-Health-Assistance.git
cd AI-Health-Assistance
```
### 2. Install Dependencies
```bash
pip install -r requirements.txt
```
### 3. Run the Application
```bash
python app.py
```
### 4. Access in Browser
Open your browser and go to:
```bash
http://localhost:5000
```
### Tech Stack
- Frontend: HTML, CSS
- Backend: Python, Flask
- Machine Learning: scikit-learn
- Deployment (optional): Render / Heroku / Localhost

### Future Improvements
- Add more accurate and diverse datasets

- Add user authentication and patient history tracking

- Improve UI with React or other frontend frameworks

- Deploy on cloud platform (e.g., Render, Firebase, AWS)
