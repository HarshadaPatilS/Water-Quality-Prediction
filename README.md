# Water-Quality-Prediction
Edunet Foundation Project

Sinhgad Institute of Technology
- Harshada Patil
- Vaishnavi Shinde

# Problem Statement
Access to clean and safe water is a fundamental necessity for human health. Contaminated water can lead to severe health issues such as gastrointestinal diseases, infections, and poisoning due to the presence of harmful substances like bacteria, heavy metals, and chemicals. This study aims to develop a machine learning-based predictive model to classify water quality based on various chemical and physical attributes.

Key Objectives:
- Develop a machine learning model to classify water as safe or unsafe for consumption.
- Analyze and preprocess water quality data to improve predictive accuracy.
- Apply different ML algorithms and compare their effectiveness.
- Deploy a functional model for real-time water quality prediction.
- Propose future enhancements for better accuracy and scalability.

# Dataset
To train and validate the model, an online dataset containing water quality parameters is used. The dataset includes various features that determine water purity:
- pH Level – Acidity or alkalinity of water.
- Dissolved Oxygen (DO) – Essential for aquatic life, indicating pollution levels.
- Total Suspended Solids (TSS) – Measures turbidity and sediment in water.
- Temperature – Affects chemical and biological reactions.
- Total Nitrogen (TPN) – Essential for biological growth but harmful in excess.
- Total Phosphorus (TP) – Can lead to algal blooms.
- Turbidity – Cloudiness due to particles in water.

Source: [Public Water Quality Dataset (Kaggle/WHO/Environmental Agencies)]

Size: Approx. 10,000+ samples with labeled outcomes (Safe/Unsafe).

# Methodology
The solution follows a structured machine learning pipeline:
- Data Collection & Cleaning – Handle missing values, outliers, and normalize features.
- Exploratory Data Analysis (EDA) – Identify key patterns in water quality data.
- Feature Engineering – Select most influential features.
- Model Selection & Training – Train multiple ML models.
- Evaluation & Optimization – Compare models, tune hyperparameters.
- Deployment – Build an API or web dashboard for predictions.

# Conclusion
The developed machine learning model effectively predicts water quality safety with high accuracy. The Random Forest and Gradient Boosting models performed the best, offering over 90% accuracy in classification. The predictive model can be used to automate water quality testing in rural areas where manual testing is expensive and time-consuming.
