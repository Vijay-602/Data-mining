# Data-mining
# Tourist Attraction Recommendation System

## Overview
This project is a web application that recommends tourist attractions based on user preferences using machine learning models. The system integrates data processing, model training, and a web-based interface to deliver real-time predictions to users. The application utilizes Flask for the backend, HTML/CSS/JavaScript for the frontend, and pre-trained models stored as pickle files.

## Project Structure

├── Tourism_Dataset/                     # Raw dataset files for analysis and model training
├── .gitattributes                       # Git attributes configuration
├── .python-version                     # Python version file
├── README.md                            # Project documentation
├── Mining_Report.pdf                    # Report detailing data mining process and findings
├── mining85.html                        # HTML report for data mining insights
├── requirements.txt                     # List of required Python packages
├── desktop.ini                          # Windows system file (can be ignored)

# Data Processing and Integration
├── cleaned_discretized_tourism_data.csv # Cleaned and discretized dataset used for modeling
├── integrated_data.csv                  # Processed and integrated dataset
├── data_integration.py                  # Script for integrating raw datasets

# Feature Engineering and Encoding
├── X.pkl                                # Feature matrix for model training
├── country_onehot_encoder2.pkl          # One-hot encoder for country features
├── onehot_encode_country-task3.pkl      # One-hot encoder specific to task 3
├── labelencoder-task3.pkl               # Label encoder for task 3 predictions
├── label_encoders.pkl                   # General label encoder used in the project
├── label_encoders2.pkl                  # Label encoder for additional tasks
├── label_encoders3.pkl                  # Label encoder for specific models

# Model Training and Pre-trained Models
├── random_forest_model.pkl              # Random Forest model for predictions
├── random_forest_models-task2-st3.pkl   # Random Forest model for task 2 predictions
├── model_1.pkl                          # Pre-trained model for predicting visit months
├── model_2.pkl                          # Pre-trained model for predicting attractions
├── model_2_3.pkl                        # Pre-trained model for predicting attraction types
├── model_3.pkl                          # Pre-trained model for attraction recommendations
├── attraction_models2.pkl               # Pre-trained model for attraction predictions

# Application Code
├── app.py                               # Main Flask application script
├── mining_project.py                    # Python script for data mining and analysis



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
