# Data-mining
# Tourist Attraction Recommendation System

## Overview
This project is a web application that recommends tourist attractions based on user preferences using machine learning models. The system integrates data processing, model training, and a web-based interface to deliver real-time predictions to users. The application utilizes Flask for the backend, HTML/CSS/JavaScript for the frontend, and pre-trained models stored as pickle files.

## Project Structure

├── Tourism_Dataset/                     # Raw dataset files for analysis and model training
├── integrated_data.csv                  # Processed and integrated dataset
├── cleaned_discretized_tourism_data.csv # Cleaned dataset used for modeling
├── country_onehot_encoder2.pkl          # One-hot encoder for country features
├── labelencoder-task3.pkl               # Label encoder for Task 3 predictions
├── label_encoders.pkl                   # General label encoder for all models
├── label_encoders2.pkl                  # Label encoder for additional tasks
├── onehot_encode_country-task3.pkl      # One-hot encoder for Task 3
├── attraction_models2.pkl               # Pre-trained model for attraction predictions
├── model_1.pkl                          # Model for predicting attraction types
├── model_2_3.pkl                        # Model for predicting attractions and months
├── model_3.pkl                          # Model for attraction recommendations
├── random_forest_model.pkl              # Random forest model for predictions
├── random_forest_models-task2-st3.pkl   # Random forest model for Task 2 and 3
├── app.py                               # Main Flask application script
├── data_integration.py                  # Script for integrating raw datasets
├── mining_project.py                    # Python script for data mining and analysis
├── Mining_Report.pdf                    # Data mining process and findings
├── README.md                            # Project documentation
├── mining85.html                        # HTML report with data mining insights
├── .gitattributes                       # Git attributes configuration
├── .python-version                      # Python version used for the project
├── desktop.ini                          # System file (can be ignored)
├── requirements.txt                     # List of required Python packages
├── X.pkl                                # Feature matrix for model training





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
