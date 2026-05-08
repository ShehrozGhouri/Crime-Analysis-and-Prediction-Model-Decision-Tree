# 👮‍♂️ Crime Type Prediction using Decision Trees

## 📌 Project Overview
This project applies a **Decision Tree Classifier** to predict the category of a crime based on geographical and temporal features. The model is designed to assist in resource allocation by predicting the likely nature of an incident and assigning a response priority level.

## 🛠️ Key Features
- **Classification Engine:** Implements a Scikit-Learn `DecisionTreeClassifier` with Entropy-based splitting.
- **Categorical Encoding:** Utilizes `LabelEncoder` to transform text-based locations and days into machine-readable data.
- **Priority Logic:** Includes a custom post-prediction script to categorize results into Priority Levels (1 to 4) for emergency response simulation.
- **Explainable AI:** Generates a "Logic Map" (Tree Visualization) and Feature Importance bars to explain how the model reaches its conclusions.

## 📋 Data Features
The model analyzes 10 specific features:
- **Spatial:** Location Description, District, Ward, Community Area.
- **Temporal:** Month, Day, Hour, Day of Week.
- **Flags:** Arrest Made (Yes/No), Domestic Incident (Yes/No).
