# Vehicle_Booking_System
📌 Overview
While there are countless online platforms for booking travel vehicles, a significant gap exists when it comes to reserving farming vehicles. This project addresses that need by introducing a machine learning-powered vehicle booking system that enables users to book either travel or farming vehicles based on their availability.
🤖 Machine Learning Integration
The system is powered by XGBoost, a high-performance machine learning algorithm known for its speed and accuracy. A custom dataset was created for this project, containing:
53% farming vehicles
47% travel vehicles
Each record in the dataset includes:
Vehicle Type (Farming or Traveling)
Vehicle Name
Cost
Owner Name
Owner Contact
Availability (Yes/No)
🛠️ Data Processing & Model Training
One-Hot Encoding is applied to convert categorical variables into numerical format.
The dataset is split into training and testing sets.
Model performance is evaluated using:
Accuracy
Precision
Recall
F1-Score
Confusion Matrix
ROC Curve
📈 Results
The XGBoost model achieved an accuracy of 56.54%, outperforming traditional models like Logistic Regression.
The performance metrics are visualized using heatmaps and ROC curves for better interpretability.
