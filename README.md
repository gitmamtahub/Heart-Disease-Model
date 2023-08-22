# Heart-Disease-Model
Diagnosis of Heart Disease from health details like BMI, Race, Age, Smoking, Asthma, Diabetic, etc.
Also physically Active, Skin cancer, Kidney Disease, Sleep time, etc.
Main Focus is no Heart Disease patient should be left undetected
In ML terms False Negative cases should be as low as possible near to null
Means If Patient is having heart disease but Reports are negative i.e. False Negative
The Confusion Matrix created has four different quadrants: (for Python)
TN    FP
FN    TP
True Negative (Top-Left Quadrant)
False Positive (Top-Right Quadrant)
False Negative (Bottom-Left Quadrant)
True Positive (Bottom-Right Quadrant)

Two Major Scenarios ----
First
To learn how HeartDisease Diagniosis is dependent on different features
EDA is done on Data with HeartDisease and different features pattern w.r.t. Gender
Second
Data is imbalance(81%=not having Heart Disease, 9%=having Heart disease
1) Balance by count of having Heart Disease = count of not having Heart Disease
2) SMOTE(0.6)
