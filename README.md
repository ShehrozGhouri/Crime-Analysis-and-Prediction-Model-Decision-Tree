# 👮‍♂️ Crime Type Prediction using Decision Trees

## 📌 Project Overview
This project applies a **Decision Tree Classifier** to predict the category of a crime based on geographical and temporal features. The model is designed to assist in law enforcement resource allocation by predicting the likely nature of an incident and assigning an emergency response priority level.

## 🛠️ Key Features
* **Classification Engine:** Implements a Scikit-Learn `DecisionTreeClassifier` utilizing Information Gain (Entropy-based splitting) to build logical decision paths.
* **Categorical Encoding:** Utilizes `LabelEncoder` to cleanly transform text-based locations, districts, and days into structured machine-readable values.
* **Priority Logic:** Includes a custom post-prediction mapping pipeline to categorize results into dynamic Priority Levels (1 to 4) for dispatch optimization.
* **Explainable AI (XAI):** Generates an interpretable Tree Visualization graph and Feature Importance metrics to transparently showcase how the model reaches its conclusions.

## 📋 Data Features
The model analyzes 10 specific features divided into three operational categories:
* **Spatial Features:** Location Description, District, Ward, Community Area.
* **Temporal Features:** Month, Day, Hour, Day of Week.
* **Incident Flags:** Arrest Made (Boolean/Binary), Domestic Incident (Boolean/Binary).

## 💻 Tech Stack
* **Language:** Python 3.x
* **Data Processing:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (`DecisionTreeClassifier`, `LabelEncoder`, `train_test_split`)
* **Visualization:** Matplotlib, Seaborn, Graphviz (for tree plot export)

---

## 🚀 How to Run the Code

1.  **Clone this repository:**
    ```bash
    git clone [https://github.com/ShehrozGhouri/Crime-Analysis-and-Prediction-Model-Decision-Tree.git](https://github.com/ShehrozGhouri/Crime-Analysis-and-Prediction-Model-Decision-Tree.git)
    cd Crime-Analysis-and-Prediction-Model-Decision-Tree
    ```

2.  **Install Required Dependencies:**
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn
    ```

3.  **Execute the Script:**
    Run your main training script or Jupyter Notebook to process the raw temporal/spatial attributes, build the decision paths, and view the feature importance scores.
