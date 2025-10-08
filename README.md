# Real-Time-Stress-Monitoring-using-Wearable-Sensor-Data

This project focuses on building a machine learning model to monitor and classify human stress levels in real-time using data collected from wearable sensors. The dataset includes physiological parameters such as humidity, temperature, and step count, which are analyzed to predict different levels of stress.

The goal is to demonstrate how data from common wearable devices (like smartwatches or fitness bands) can be leveraged for mental health monitoring and well-being analysis through data preprocessing, visualization, and predictive modeling.

⚙️ Technologies Used

Python

NumPy, Pandas – Data manipulation and preprocessing

Matplotlib, Seaborn – Data visualization and correlation analysis

Scikit-learn – Machine learning algorithms and evaluation

🧩 Workflow

Data Collection & Cleaning

The dataset (Stress-Lysis.csv) contains sensor-based metrics such as step count, humidity, and temperature.

Checked and removed duplicate or missing values to ensure data consistency.

Exploratory Data Analysis (EDA)

Generated pivot tables and correlation matrices to explore relationships between features and stress levels.

Visualized stress distribution, temperature, and humidity variations using histograms, boxplots, and pie charts.

Feature Engineering & Data Splitting

Independent variables (X) and target (Stress_Level) were separated.

Split the dataset into training and testing sets using an 80:20 ratio.

Model Training and Evaluation
Implemented multiple ML models to predict stress levels:

K-Nearest Neighbors (KNN)

Gaussian Naive Bayes (GNB)

Logistic Regression

Linear Regression (for comparison)

Evaluated models using accuracy score and confusion matrix to measure performance.

Result Visualization

Compared model accuracies using visual charts for better interpretability.

Displayed stress level distribution insights for each physiological parameter.

📊 Key Results

Models successfully classified stress levels based on wearable sensor data.

Demonstrated that machine learning can detect stress patterns using environmental and activity-related signals.

Logistic Regression and KNN showed promising accuracy among tested models.
