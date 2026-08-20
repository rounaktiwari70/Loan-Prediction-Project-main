# Loan-Prediction-Project-main
Lung Cancer Prediction AI App
Features
Interactive Web Interface: Built with Streamlit.
Real-time Prediction: Uses a Random Forest Classifier to predict risk (Low, Medium, High).
Customizable Inputs: Adjust patient age, lifestyle habits, and symptoms to see how they affect risk.
Installation
Open your terminal/command prompt.
Navigate to the project directory:
cd "C:\PYTHON PROGRAMMING\Lungs Cancer Prediction"
Install the required dependencies:
pip install -r requirements.txt
How to Run
Run the application using the following command:
streamlit run app.py
A browser window will open automatically with the application.
Use the sidebar to input patient data and click "Predict Risk Level" to see the result.
Files
app.py: The main application script.
train_model.py: Script used to train the model (run this if model artifacts are missing).
data.csv: Source dataset.
*.joblib: Serialized model artifacts (Model, Scaler, Encoder).
