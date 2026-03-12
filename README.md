Blood Pressure Prediction using Random Forest
📌 Overview
This project demonstrates how to use a Random Forest Regressor to predict systolic and diastolic blood pressure based on patient details such as age, weight, pulse rate, and activity level. It also evaluates the model’s performance and provides a simple interface for users to input patient data and receive predictions.

⚙️ Features
- Data preprocessing with StandardScaler
- Train-test split for model evaluation
- Random Forest regression for multi-output prediction
- Performance metrics: Mean Absolute Error (MAE) and R² Score
- Interactive patient input for real-time predictions
- Visualization of prediction accuracy using Matplotlib

📂 Dataset
The dataset is a small synthetic collection with the following features:
- age: Patient’s age (years)
- weight: Patient’s weight (kg)
- pulse_rate: Resting pulse rate (beats per minute)
- activity_level: Activity level (1 = low, 3 = high)
- systolic_bp: Systolic blood pressure (mmHg)
- diastolic_bp: Diastolic blood pressure (mmHg)

🛠️ Requirements
Install the required Python libraries before running the script:
pip install pandas numpy matplotlib scikit-learn



🚀 Usage
- Clone or download the project files.
- Run the script in your terminal:
python bp_prediction.py
- The program will:
- Train the Random Forest model
- Display model performance metrics
- Prompt you to enter patient details
- Output predicted systolic and diastolic blood pressure
- Show a scatter plot comparing actual vs predicted systolic BP

📊 Example Output
Model Performance
------------------
Mean Absolute Error: 2.5
R2 Score: 0.92

Enter Patient Details
Age: 45
Weight: 75
Pulse Rate: 78
Activity Level (1-3): 2

Predicted Blood Pressure
Systolic: 124
Diastolic: 81



📈 Visualization
The script generates a scatter plot:
- X-axis: Actual systolic blood pressure
- Y-axis: Predicted systolic blood pressure
- Helps assess how well the model fits the data

🔮 Future Improvements
- Expand dataset with real-world medical records
- Add more features (e.g., BMI, lifestyle factors)
- Implement hyperparameter tuning for better accuracy
- Build a GUI or web app for easier patient interaction
