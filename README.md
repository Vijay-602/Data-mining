# Data-mining
# Tourist Attraction Recommendation System

## Overview
This project is a web application that recommends tourist attractions based on user preferences using machine learning models. The system integrates data processing, model training, and a web-based interface to deliver real-time predictions to users. The application utilizes Flask for the backend, HTML/CSS/JavaScript for the frontend, and pre-trained models stored as pickle files.


## Getting Started

### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Flask
- Required Python packages listed in `requirements.txt`

### Project Description
- **Data Integration**: The `data_integration.py` script integrates raw datasets into a unified format.
- **Data Cleaning and Discretization**: Preprocessed data is saved in `cleaned_discretized_tourism_data.csv`.
- **Model Training**: Machine learning models are trained and stored as pickle files for efficient predictions.
- **Web Application**: The `app.py` script manages the web interface, handling user inputs and displaying recommendations.

### Models
- `model_1_1.pkl`: Predicts top attraction types based on user preferences.
- `model_1_2.pkl`: Suggests specific attractions based on attraction type.
- `model_2_3.pkl`: Predicts the best months to visit attractions.
- `model3_1.pkl`: Provides personalized attraction recommendations.

### Contributors

- **Rohan Aditya** (Roll No: 220741) - [praditya22@iitk.ac.in](mailto:praditya22@iitk.ac.in)
- **Vijay Kumar** (Roll No: 220602) - [mvijayk22@iitk.ac.in](mailto:mvijayk22@iitk.ac.in)
- **Maradana Kasi Sri Roshan** (Roll No: 220633) - [mkasi22@iitk.ac.in](mailto:mkasi22@iitk.ac.in)
- **Laveti BhanuPrakash** (Roll No: 220583) - [lbhanu22@iitk.ac.in](mailto:lbhanu22@iitk.ac.in)
