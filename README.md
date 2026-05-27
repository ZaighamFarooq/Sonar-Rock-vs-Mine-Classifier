# Sonar-Rock-vs-Mine-Classifier
Sonar signal classification using Logistic Regression to predict whether,  an underwater object is a Rock or a Mine

•AboutThe dataset•
- 208 samples of sonar signals bounced off different objects
- 60 features: Energy at different frequencies (0.0 to 1.0 normalized)
- 2 classes 'M' = Mine (metal cylinder), 'R' = Rock

*What This Project Does*
1. Load Data --> Read sonar signals from CSV
2. Preprocess --> Encode text labels (R/M) --> numbers (0/1)
3. Split Data --> 90% training, 10% testing
4. Train Model --> Logistic Regression learns patterns
5. Evaluate --> Check accuracy on training & test data
6. Predict --> Classify new sonar readings

*Tech*
- Python
- Pandas (data handling)
- NumPy (arrays)
- Scikit-learn (ML model)

*Results*
Training Accuracy: 83.4%
Test Accuracy: 76.1%
