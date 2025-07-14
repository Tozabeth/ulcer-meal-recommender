# Ulcer Meal Recommendation System 🥣

This project predicts the likelihood of ulcer pain triggers based on user input such as symptoms, medication history, and meal habits. It then recommends soothing or safe African meals accordingly.

## 🌟 Project Overview

Many people living with ulcers struggle to identify which meals might worsen their symptoms. This project offers a simple solution: by inputting key information, the system predicts the likelihood of a flare-up and recommends meals that are safer to consume.

You can upload your data, make predictions, and receive dietary suggestions through the model built in Google Colab. The notebook includes data preprocessing, model training, evaluation, and logic for meal recommendations based on prediction outcomes.

---
## 📊 Model Details

| Feature Type       | Examples                                                                 |
|--------------------|--------------------------------------------------------------------------|
| Multi-label        | Meals, Symptoms, Trigger Causes                                          |
| Binary             | Took NSAIDs, Skipped Meals, Ate Late, Family History, H. pylori Infection |
| Categorical        | Duration of symptoms, Time of medication, etc.                                 |


- **Algorithm**: Random Forest Classifier
- **Encoding Techniques**:
  - `LabelEncoder` for categorical features
  - `MultiLabelBinarizer` for list-based features
- **Performance**: Evaluated using accuracy and F1-score

## 🔍 Features
- Trained a machine learning model using symptom and lifestyle data
- Built a meal recommendation system
- Used model predictions to drive healthy meal choices
- Dataset includes real-world ulcer triggers and African meal suggestions

## 📁 Files
- `Ulcer.ipynb` - Google Colab notebook containing all training and inference code
- `*.pkl` - Trained model and encoders (optional but recommended)
- `README.md` - You're reading it 😊

## 💡 How to Use
Open the notebook, follow the steps, and adjust inputs for new predictions. You can also integrate the model into an API using FastAPI.

