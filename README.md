# AI-Driven-Multimodal-Data-Fusion-system-for-cardiac-arrest-risk-prediction-
Hybrid machine learning model for cardiac arrest risk prediction using Random Forest on clinical data and SVM on ECG images with late fusion for improved accuracy.

This project implements a hybrid machine learning framework to predict the risk of cardiac arrest by combining structured patient data (CSV files) with ECG image analysis.

🧮 Random Forest (RF) is applied to clinical data (age, gender, vitals, cholesterol, BP, etc.) to identify key risk factors.

🫀 Support Vector Machine (SVM) is used to classify ECG images into normal/abnormal patterns for cardiac distress detection.

🔗 A late fusion technique integrates predictions from both models, giving a more reliable and accurate cardiac arrest risk prediction.

📊 The system includes data preprocessing, model training, evaluation, and visualization, making it practical for clinical decision support.

Tech Stack:

Python 3.x

Scikit-learn, NumPy, Pandas

OpenCV, Matplotlib

TensorFlow/Keras (for preprocessing/encoding)

Google Colab / Jupyter Notebook
