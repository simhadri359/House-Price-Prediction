🏠 Bangalore House Price Prediction – End-to-End ML Web Application
📌 Problem Statement :
Real estate pricing is influenced by multiple factors such as location, square footage, number of  bedrooms, and amenities. Manual estimation often leads to inconsistent and inaccurate pricing.
The goal of this project is to build a machine learning model that predicts house prices in     Bangalore and deploy it as a web application for real-time user interaction.

🎯 Objectives :
*Perform data cleaning and preprocessing
*Apply feature engineering techniques
*Train and validate a regression model
*Deploy the trained model using Flask
*Build a simple frontend for real-time prediction

📊 Dataset :
Bangalore House Price Dataset
Includes features such as:
  Location
  Total Square Footage
  Number of Bedrooms (BHK)
  Number of Bathrooms
  Price

🔍 Data Preprocessing :
*Removed irrelevant columns
*Handled missing values
*Converted categorical variables (location encoding)
*Removed rare locations to reduce dimensionality
*Detected and removed outliers using domain-based filtering
*Applied train-test split (80-20)

🤖 Model Used :
  *Linear Regression (Supervised Learning) : 
  *Why Linear Regression?
    -Suitable for continuous target prediction
    -Interpretable model
    -Strong baseline before moving to complex models

📈 Model Performance :
  *Test Score (R²): 0.8452
  *Cross-Validation (5-fold ShuffleSplit):
      [0.8243, 0.7716, 0.8508, 0.8083, 0.8365]
  *Validation Technique :
    -Used ShuffleSplit cross-validation to ensure model generalization and avoid dependency on a       single train-test split.

🌐 Deployment Architecture :
Frontend (HTML, CSS, JavaScript)
⬇
Flask Backend (Python)
⬇
Trained ML Model (Pickle File)
⬇
Prediction Output

⚙️ Tech Stack :
-Python
-Pandas
-NumPy
-Scikit-learn
-Flask
-HTML
-CSS
-JavaScript

🚀 How to Run the Project :
1️⃣ Clone the repository :
  git clone https://github.com/simhadri359/House-Price-Prediction.git
  cd House-Price-Prediction
2️⃣ Install dependencies :
  pip install -r requirements.txt
3️⃣ Run Flask Server :
  python app.py
4️⃣ Open in Browser :
  http://127.0.0.1:5000/

🧠 Key Learnings :
*Feature engineering significantly impacts model performance
*Outlier removal improves prediction stability
*Cross-validation provides realistic performance estimation
*Deployment bridges the gap between ML theory and real-world application

🔮 Future Improvements :
*Experiment with Random Forest and XGBoost
*Hyperparameter tuning
*Add model explainability (SHAP values)
*Deploy on cloud platform (AWS/GCP)
*Add real-time location-based API integration

📌 Author :
G. Simhadri
Aspiring Software Engineer | ML | DSA | Backend Development

💡 Interview Talking Points :
*Why Linear Regression as baseline
*Handling multicollinearity
*Cross-validation importance
*Model deployment workflow
*Production improvement strategies
