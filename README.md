Hospital Appointment No-Show Prediction System

 Project Overview

This project presents a Machine Learning-based web application that predicts whether a patient is likely to miss a scheduled hospital appointment (No-Show).

The system analyzes patient information and appointment-related factors to support hospitals in reducing missed appointments, improving scheduling, and making better use of healthcare resources.

 Project Objective

The primary objective is to develop a predictive model capable of identifying patients who may not attend their appointments based on different demographic, medical, and scheduling features, including:

- Age
- Gender
- Neighborhood
- Hypertension
- Diabetes
- Alcoholism
- Handicap
- SMS reminders
- Waiting time
- Appointment day
- Scholarship

 Dataset Information

Dataset: Medical Appointment No Shows

Dataset File: "KaggleV2-May-2016.csv"

Source: The dataset was originally collected from medical appointment records in Brazil and made available on Kaggle by Joni Arroba.

Dataset Description:
The dataset contains more than 110,000 appointment records, including patient demographics, medical conditions, appointment scheduling information, SMS notifications, and the final appointment attendance status.

 Machine Learning Methodology

Data
Preprocessing

Several preprocessing steps were applied to prepare the dataset for machine learning:

- Handling missing and inconsistent data
- Converting categorical variables into numerical representations
- Creating additional features such as Age Groups and Waiting Days
- Scaling numerical features when necessary
- Preparing the final dataset for model training and evaluation

 Machine Learning Models

The project uses multiple machine learning techniques, including:

- Random Forest Classifier
- Decision Tree Classifier
- StandardScaler for feature scaling

The models were trained and evaluated to determine their ability to classify appointments as either Show or No-Show.

Model Evaluation

The performance of the classification models was assessed using several evaluation metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

These metrics provide a broader view of the model's classification performance rather than relying only on accuracy.

 Web Application

A web-based prediction interface was developed using Flask.

The application allows users to enter patient and appointment information and receive a prediction regarding the likelihood of a No-Show appointment.

 Main Features

- Patient information input form
- Appointment details input
- Prediction of appointment attendance
- No-show probability estimation
- Simple and user-friendly interface
- Real-time prediction through the Flask application

 Technologies Used

- Python
- Flask
- HTML / CSS
- Scikit-learn
- Pandas
- NumPy
- Joblib

 Data Analysis & Visualizations

The project includes several visual analyses to better understand the dataset and model behavior, such as:

- Correlation Heatmap
- No-Show Distribution
- Count Plots
- Feature Importance Visualization
- Data Distribution Graphs

These visualizations help identify important patterns and relationships within the appointment data.

 Limitations

The prediction system is based on historical data, so its results should be considered probabilistic predictions rather than guaranteed outcomes.

In addition, saved machine learning models may require compatible versions of Scikit-learn and related libraries when being loaded.

 Project Presentation

A presentation video demonstrating the project is available here:

https://drive.google.com/file/d/1YEwfnPTiujdKJ_c118cb54IpICkEqg_Z/view?usp=drivesdk

 Author

Haneen Mohamed

 Under the Supervision of

Dr. Mohamed El Sayeh

 How to Run the Project

Install the required Python packages:

pip install -r requirements.txt

Then start the Flask application:

python app.py

After running the application, open the provided local address in a web browser to access the prediction system.
