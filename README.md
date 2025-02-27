Disease Prediction System

This is a Flask-based web application that predicts diseases based on user-input symptoms. The application utilizes a machine learning model trained with symptom data to provide accurate predictions along with precautions, medications, diet recommendations, and suggested workouts.

Features

Predicts diseases based on symptoms entered by the user

Provides a brief description of the predicted disease

Suggests precautions, medications, and dietary recommendations

Displays recommended workouts for the predicted disease

User-friendly web interface built with Flask and HTML templates

Installation & Setup

Clone the repository:

git clone https://github.com/your-repository-name.git
cd your-repository-name

Install required dependencies:

pip install -r requirements.txt

Run the application:

python app.py

Open the browser and visit http://127.0.0.1:5000/.

Files & Directories

app.py - Main Flask application

models/svc.pkl - Pre-trained machine learning model for prediction

datasets/ - CSV files containing symptom, precaution, medication, diet, and workout data

templates/ - HTML files for the web interface

Usage

Enter symptoms separated by commas in the input field.

Submit the form to get a predicted disease.

View details, precautions, medications, and recommendations.

Contributing

Feel free to submit issues or pull requests for improvements.

License

This project is licensed under the MIT License.

