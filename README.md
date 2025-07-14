# Medical_Adherence
Situations of Patients lake of medical Adherence in Hospitals. starting for EDA To Modeling...

# Medication Adherence Predictor
Predicts patient medication non-adherence risk using health indicators

## Key Results
- AUC: 0.82 | Recall: 0.78
- Identifies 78% of non-adherent patients
- Top predictors: Chronic conditions, Income level, Mental health

## Usage
python
import joblib
model = joblib.load('models/medication_adherence_model.pkl')
# See notebooks/analysis.ipynb for prediction example
