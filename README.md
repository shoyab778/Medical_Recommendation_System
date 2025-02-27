# Disease Prediction System

## Overview
This is a Flask-based web application that predicts diseases based on user-input symptoms. The application utilizes a machine learning model trained with symptom data to provide accurate predictions. It also offers details such as disease descriptions, precautions, medications, diet recommendations, and suggested workouts.

## Features
- **Disease Prediction**: Predicts diseases based on input symptoms.
- **Disease Information**: Provides a description of the predicted disease.
- **Precautionary Measures**: Lists recommended precautions for the predicted disease.
- **Medication Suggestions**: Displays potential medications for treatment.
- **Diet Recommendations**: Suggests appropriate diets based on the disease.
- **Workout Plans**: Recommends suitable exercises for recovery.
- **User-Friendly Interface**: Built with Flask and HTML templates.

## Installation & Setup
### Prerequisites
Ensure you have Python installed on your system. You also need Flask and other dependencies.

### Steps to Install
1. **Clone the repository**:
   ```sh
   git clone https://github.com/your-repository-name.git
   cd your-repository-name
   ```
2. **Install dependencies**:
   ```sh
   pip install -r requirements.txt
   ```
3. **Run the application**:
   ```sh
   python app.py
   ```
4. **Access the application**:
   Open your browser and visit `http://127.0.0.1:5000/`.

## Project Structure
```
.
├── app.py                 # Main Flask application
├── models/
│   ├── svc.pkl            # Pre-trained machine learning model
├── datasets/
│   ├── symptoms_df.csv     # Symptom data
│   ├── precautions_df.csv  # Precautions data
│   ├── workout_df.csv      # Workout recommendations
│   ├── description.csv     # Disease descriptions
│   ├── medications.csv     # Medication recommendations
│   ├── diets.csv           # Diet recommendations
├── templates/
│   ├── index.html          # Main web page template
│   ├── about.html          # About page
│   ├── contact.html        # Contact page
│   ├── developer.html      # Developer information
│   ├── blog.html           # Blog page
└── requirements.txt        # Required dependencies
```

## Usage
1. Enter symptoms separated by commas in the input field.
2. Click **Submit** to get a predicted disease.
3. View details, precautions, medications, diets, and workout suggestions.

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests.

## License
This project is licensed under the MIT License.

