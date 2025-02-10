Hotel Reservations Cancellation Prediction
📌 Project Overview
This project predicts hotel reservation cancellations using machine learning models. By analyzing booking details such as lead time, market segment, and customer behavior, the model helps hotels optimize revenue management and reduce cancellations.

📂 Project Structure
📁 Hotel_Reservations_Cancellation_Prediction  
│-- 📁 data/                   # Dataset (if publicly available)  
│-- 📁 notebooks/               # Jupyter Notebooks for EDA & Model Training  
│-- 📁 models/                  # Saved Machine Learning Models  
│-- 📁 src/                     # Source Code (Data Preprocessing & Model Training Scripts)  
│-- ├── hotel_reservations_cancelation_prediction.py  # Main script  
│-- ├── requirements.txt        # Dependencies  
│-- ├── README.md               # Project Documentation  
│-- ├── LICENSE                 # License information  


📊 Dataset Description
The dataset contains hotel reservation records with various features that impact cancellations.

Key Features
Lead Time: Days between booking and arrival
Market Segment: Source of booking (Online, Offline, Corporate, Aviation)
Guest Info: Number of adults, children, special requests
Booking Status: Whether the reservation was canceled or not
Target Variable
Booking Status (0 = Not Canceled, 1 = Canceled)
🛠 Technologies Used
Programming Language: Python 🐍
Libraries & Tools: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
Machine Learning Models:
Decision Tree Classifier
Random Forest Classifier
Logistic Regression
🔍 Exploratory Data Analysis (EDA)
✔ Visualized booking patterns, customer preferences, and seasonality effects
✔ Identified key factors influencing cancellations (e.g., lead time, market segment)
✔ Performed feature engineering and outlier removal

🤖 Model Training & Evaluation
Decision Tree: 🎯 85% Accuracy (Best Performing Model)
Random Forest: Strong generalization but slightly lower accuracy
Logistic Regression: Performed well but less effective on complex patterns
Feature Importance
📌 Lead Time was the most significant factor in predicting cancellations.
📌 Online Bookings had a higher cancellation rate than offline bookings.
