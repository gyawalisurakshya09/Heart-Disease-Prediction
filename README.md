# Heart Disease Prediction

## About the Project
This project uses Machine Learning to predict the possibility of heart disease based on health-related features.
 It uses a Support Vector Machine (SVM) classifier to make predictions.

## Technologies Used
- Python
- Pandas and NumPy
- Scikit-learn
- Jupyter Notebook
- Streamlit 

## Project Files
- `app.py` – Application code
- `heart.ipynb` – Data preprocessing and model training
- `svm_heart.pkl` – Trained SVM model
- `scaler.pkl` – Feature scaling object
- `columns.pkl` – Input column information
- `heart.csv` – Dataset 

## Features
- Processes health-related input data
- Scales features before prediction
- Predicts the possibility of heart disease using the trained model

## How to Run
1. Clone this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy scikit-learn streamlit
   ```

3. Run the application:

   ```bash
   streamlit run app.py
   ```

## Disclaimer
This project is intended for educational purposes only. It is not a substitute for professional medical advice or diagnosis.