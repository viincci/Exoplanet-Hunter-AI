# Exoplanet Hunter AI
## Introduction
Exoplanet Hunter AI is an advanced machine learning system designed to classify exoplanet candidates from NASA's Kepler mission data with unprecedented accuracy.
## Key Features
- Advanced machine learning models for exoplanet classification
- Interactive web interface for inputting stellar observation parameters
- Real-time prediction and classification of exoplanet candidates
## Tech Stack
- Python 3.x
- FastAPI
- Flask
- scikit-learn
- TensorFlow
- Keras
- Bootstrap 5
- Chart.js
## Installation
1. Clone the repository: `git clone https://github.com/Exoplanet-Hunter-AI/Exoplanet-Hunter-AI.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Start the backend server: `uvicorn backend.app:app --host 0.0.0.0 --port 8000`
4. Start the frontend server: `flask run --host 0.0.0.0 --port 5000`
## Usage
1. Open a web browser and navigate to `http://localhost:5000`
2. Input stellar observation parameters in the prediction form
3. Submit the form to receive real-time predictions and classifications
## Environment Variables
- `API_URL`: the URL of the backend API server (default: `http://localhost:8000`)
- `SECRET_KEY`: a secret key for the Flask application (default: a random key)