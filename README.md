# AI-Driven-Multimodal-Data-Fusion-system-for-cardiac-arrest-risk-prediction-
📌 Project Overview

This project implements a hybrid machine learning framework to predict the risk of cardiac arrest by integrating structured clinical data with ECG image analysis.

Random Forest (RF): Analyzes patient data (age, vitals, cholesterol, BP, etc.) to identify key risk factors.

Support Vector Machine (SVM): Classifies ECG images into normal/abnormal categories for detecting cardiac distress.

Late Fusion: Combines predictions from RF (30%) and SVM (70%) to improve diagnostic accuracy and provide a more reliable assessment.

The system assists healthcare professionals in early detection, risk assessment, and timely intervention for better patient outcomes.

⚙️ Features

🧮 Clinical Data Analysis with Random Forest

🫀 ECG Image Classification with SVM

🔗 Fusion of multimodal data for enhanced accuracy

📊 Visualization of predictions, feature importance, and model evaluation

🔒 Focus on data security and scalability for healthcare settings

🛠️ Tech Stack

Programming Language: Python 3.x

Libraries/Frameworks:

Scikit-learn (Random Forest, SVM)

Pandas, NumPy (data processing)

OpenCV (ECG image preprocessing)

Matplotlib (visualization)

TensorFlow/Keras (encoding & preprocessing support)

Environment: Jupyter Notebook / Google Colab

📊 Results

Random Forest (Clinical Data): 100% accuracy on test set

SVM (ECG Images): 94% accuracy

Fusion Model: Improved overall reliability compared to single-model approaches
