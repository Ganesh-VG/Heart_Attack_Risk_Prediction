# Heart Attack Risk Prediction Project

## Project Overview
This project aims to predict the risk of heart attacks using machine learning models. The dataset includes various features such as age, BMI, cholesterol levels, and lifestyle factors (smoking, alcohol intake, and physical activity). We employed multiple machine learning techniques, including ensemble methods like Random Forest and LightGBM, to achieve the best predictive performance.

## Dataset
The dataset contains anonymized patient information with the following key features:
- **Age**
- **Height**
- **Weight**
- **Systolic_BP**
- **Diastolic_BP**
- **Cholesterol Levels**
- **Glucose Levels**
- **Lifestyle Factors**: Smoking, Alcohol Intake, Physical Activity
- **Target Variable**: Presence or absence of heart disease

## Models Used
- Random Forest Classifier
- LightGBM Classifier
- Model Ensemble (Stacking)

## Best Model Performance
- **Accuracy**: 73%
- **Precision**: 73%
- **Recall**: 73%
- **F1 Score**: 72%

## Feature Importance
Feature importance analysis revealed that BMI, MAP, and age are the most influential predictors of heart disease risk. Lifestyle factors like smoking, alcohol intake, and physical activity had lower importance but are still relevant.

## Conclusion
The ensemble model using Random Forest and LightGBM achieved the best performance, with balanced accuracy, precision, recall, and F1 scores. The results indicate that BMI, MAP, and age are critical predictors of heart attack risk.

## Recommendations
### Data Collection
- Collect more granular data for lifestyle factors such as the intensity of physical activity, detailed smoking habits, and alcohol consumption metrics.

### Feature Enhancement
- Consider additional features such as:
  - Unhealthy diet patterns
  - Family history of cardiovascular diseases
  - Genetic disorders
  - Environmental factors (air pollution, UV radiation, climate changes)

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/Ganesh-VG/Heart_Attack_Risk_Prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Heart_Attack_Risk_Prediction
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter notebook or Python script to train the model and evaluate performance.

## Acknowledgements
- This project was inspired by the need to better understand and predict heart attack risks using machine learning.
- Special thanks to the open-source community and the authors of the libraries used in this project.


