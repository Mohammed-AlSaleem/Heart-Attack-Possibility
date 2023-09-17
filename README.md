# Heart-Attack-Possibility
STAT 230: Linear Models

## Abstract
Heart attacks are dangerous situations, so it is important to find a way to predict them and know the people who have a high chance to get heart attacks. High chance or low chance is a classification problem, and Logistic Regression is a classification algorithm that is used to predict a categorical variable. For analysis in this report, the heart disease dataset from the UCI Machine Learning Repository will be used. From 13 attributes the individual will be classified as having high chance of heart attack or a low chance, attributes like age, sex, etc. Moreover, backward stepwise selection is done to find the most significant predictors.

## Attributes Information:
1. (age) in years
2. (sex) (1 = male; 0 = female)
3. (cp) chest pain type (1= typical angina, 2 = atypical angina, 3 = non-anginal pain, 4 = asymptomatic)
4. (trestbps) resting blood pressure (in mm Hg)
5. (chol) serum cholestoral in mg/dl
6. (fbs) fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
7. (restecg) resting electrocardiographic results
(0= normal, 1=having ST-T wave abnormality, 2= showing probable or definite left ventricular
hypertrophy by Estes' criteria)
8. (thalach) maximum heart rate achieved
9. (exang) exercise-induced angina (1 = yes; 0 = no)
10. (oldpeak) ST depression induced by exercise relative to rest
11. (slope) the peak exercise ST segment slope (1= upsloping, 2= flat, 3= down sloping)
12. (ca) number of major vessels (0-3) colored by fluoroscopy
13. (thal) (1 = normal; 2 = fixed defect; 3 = reversible defect)
14. (target) the predicted attribute (0= less chance of heart attack, 1= more chance of heart attack)
