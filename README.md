# INFO7390-Heart_Failure_Prediction_And_Analytics


Advanced Data Science | INFO 7390 | Summer 2023

## Objective

Heart failure, a debilitating condition where the heart's ability to pump blood efficiently is compromised, has a substantial global impact. This project employs supervised machine learning algorithms to predict accurate results relevant to one's heart health, aiming to save lives through correct predictions of heart conditions.

## Target Variable

We have chosen to target 'HeartDisease' as the variable due to its significant healthcare impact, clinical relevance, preventive potential, quality data, machine learning challenge, and public health value.

## Machine Learning Algorithms

The following machine learning algorithms were employed for heart disease prediction:

1. Decision Tree
2. Random Forest
3. Multilayer Perceptron Classifier
4. Support Vector Machine
5. Extra Tree
6. Logistic Regression
7. K-Nearest Neighbors
8. Gradient Boosting Classifier
9. Stacking Classifier

## Data Set Description

The dataset contains 11 features that can be used to predict the possibility of heart disease:

1. Age: age of the patient [years]
2. Sex: sex of the patient [M: Male, F: Female]
3. ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
4. RestingBP: resting blood pressure [mm Hg]
5. Cholesterol: serum cholesterol [mm/dl]
6. FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
7. RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality, LVH: left ventricular hypertrophy]
8. MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
9. ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
10. Oldpeak: ST depression [Numeric value]
11. ST_Slope: slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
12. HeartDisease: output class [1: heart disease, 0: Normal]

## Additional Analytics & Conclusion

Among the algorithms employed, Random Forest and Stacking Classifier demonstrated the top performance with the following metrics:

**Random Forest**  
- Train Accuracy: 92.52%
- Test Accuracy: 85.814%
- F1 Score: 86.64%

**Stacking Classifier**  
- Train Accuracy: 93.45%
- Test Accuracy: 84.42%
- F1 Score: 85.71%

## Scope of Future Work

While Random Forest and Stacking Classifier showcased top performance, future work involves integrating ECG analytics to enhance predictions and achieve even higher accuracies, contributing to saving lives on humanitarian grounds.

## Dataset Link: https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

## License

This project is licensed under the [MIT License](LICENSE).
