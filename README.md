Wafer (In electronics), also called a slice or substrate, is a thin slice of semiconductor, such as a crystalline silicon (c-Si), used for fabrication of integrated circuits and in photovoltaics, to manufacture solar cells.
The inputs of various sensors for different wafers have been provided. The goal is to build a machine learning model which predicts whether a wafer needs to be replaced or not (i.e whether it is working or not) nased on the inputs from various sensors

There are two classes: +1 and -1: +1: Means that the wafer is in a working condition and it doesn't need to be replaced. -1: Means that the wafer is faulty and it needa to be replaced.

By leveraging advanced algorithms, this project enables timely fault detection, reducing manufacturing costs and improving product quality.

The system processes sensor data from the production line, pre-processes the data, trains models, and deploys the optimal model in a scalable, user-friendly web application.

Features

Fault Prediction: Accurate classification of wafer faults based on sensor data.
Data Preprocessing: Automated handling of missing values, outliers, and feature scaling.
Model Optimization: Evaluation of multiple algorithms like Random Forest, KMeans, and XGBoost for optimal performance.
Web Deployment: User-friendly interface built with Flask for real-time predictions.
Cloud Integration: Scalability and automated deployment using AWS Elastic Beanstalk.
Technologies Used

Languages: Python
Libraries and Frameworks: Scikit-learn, Flask, Pandas, NumPy, XGBoost
Cloud Services: AWS Elastic Beanstalk
Machine Learning Algorithms: Random Forest, KMeans, XGBoost
Development Tools: Git, PyCharm
Project Workflow

Data Collection: Gathered wafer sensor data for training and testing.
Preprocessing:
Addressed missing values and outliers.
Scaled features for improved model performance.
Model Training:
Experimented with various machine learning models.
Achieved 94% accuracy with Random Forest as the best-performing model.
Web Application:
Developed a Flask-based interface for fault prediction.
Integrated model with backend APIs for seamless interaction.
Deployment:
Deployed the application on AWS Elastic Beanstalk for scalability and accessibility.

Future Improvements
Incorporate deep learning models for enhanced accuracy.
Enable real-time streaming of sensor data for immediate fault detection.
Integrate advanced visualization tools for better interpretability.
