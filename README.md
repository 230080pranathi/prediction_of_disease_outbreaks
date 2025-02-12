📌 Overview
This is a machine learning-based disease prediction system designed to predict whether a person has diabetes, heart disease, or Parkinson’s disease based on user inputs. The system uses Streamlit for the frontend interface and ML models for prediction.


📁 Project Structure:
disease_prediction/
│── datasets/
│   ├── diabetes.csv
│   ├── heart.csv
│   ├── parkinsons.csv
│── training_modules/
│   ├── diabetes_model.sav
│   ├── heart_model.sav
│   ├── parkinson.sav
│── web.py
│── README.md
│── requirements.txt

🛠️ Technologies Used
Python 🐍
Streamlit (for UI)
Scikit-learn (for model training)
Pandas & NumPy (for data processing)
Pickle (for model storage)

⚡ Features
✔ Predicts Diabetes, Heart Disease, and Parkinson’s Disease
✔ User-friendly Streamlit interface
✔ Models trained on real-world datasets
✔ Fast and accurate results

🚀 How to Run
1️⃣ Clone the repository:
git clone https://github.com/YourUsername/disease-prediction
cd disease-prediction

2️⃣ Install dependencies:
pip install -r requirements.txt


3️⃣ Run the application:
streamlit run web.py


4️⃣ Enter the required details and get predictions!

📊 How It Works
User inputs health parameters through the Streamlit interface.
Pre-trained ML models process the data.
The prediction result is displayed on the UI.

🏗 Future Improvements
Add predictions for more diseases
Improve model accuracy with advanced algorithms
Deploy on cloud platforms for wider accessibility

