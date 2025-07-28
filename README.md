Live Application:https://c0cad908ae27.ngrok-free.app/
<img width="1902" height="939" alt="Screenshot 2025-07-28 233613" src="https://github.com/user-attachments/assets/df116297-54d9-494e-a4ec-68420d61e63e" />

🧠 The Machine Learning Pipeline

The predictive power of this application comes from a carefully constructed machine learning pipeline.

Algorithm: XGBoost Regressor was chosen for its high performance and robustness.
Features: The model is trained on the following features:
Age
Gender
Education Level
Job Title
Years of Experience
Preprocessing:
Categorical features (Gender, Education Level, Job Title) are encoded using LabelEncoder.
Numerical features are scaled using StandardScaler to ensure the model performs optimally.
Performance: The model achieved an R² Score of 94.58% on the held-out test set, indicating that it explains a very high percentage of the variance in salary data.
Persistence: The entire pipeline, including the trained model, encoders, and scaler, is saved into a single salary_predictor.pkl file using joblib for easy and error-free loading during inference.
