# 📦 Package Damage Risk Predictor

A machine learning project that predicts the potential **damage risk of a package before dispatch** using package and delivery-related information.

The project uses a **Random Forest Classifier** and provides a simple **Gradio interface** for making predictions.

## 🎯 Project Objective

The goal of this project is to demonstrate how machine learning can be used to classify packages into different damage-risk categories based on factors such as:

* Package weight
* Package size
* Fragility level
* Delivery distance
* Number of handling points
* Packaging quality
* Weather risk

The model predicts one of three categories:

* 🟢 Low Damage Risk
* 🟡 Medium Damage Risk
* 🔴 High Damage Risk

## 🤖 Machine Learning Model

**Algorithm:** Random Forest Classifier

The dataset was divided into:

* **80% Training Data**
* **20% Testing Data**

The model achieved approximately **80% accuracy** on the test set.

> Note: The dataset used in this project is synthetically generated for educational and demonstration purposes. The accuracy should not be interpreted as real-world package-damage prediction performance.

## 🛠️ Technologies Used

* Python
* Pandas
* Scikit-learn
* Random Forest
* Joblib
* Gradio
* Google Colab

## 📊 Dataset Features

| Feature             | Description                    |
| ------------------- | ------------------------------ |
| `package_weight`    | Weight of the package in kg    |
| `package_size`      | Package size rating            |
| `fragility_level`   | How fragile the package is     |
| `distance`          | Delivery distance in km        |
| `handling_points`   | Number of handling points      |
| `packaging_quality` | Quality of packaging           |
| `weather_risk`      | Weather-related risk indicator |
| `damage_risk`       | Target variable                |

## 🔄 Project Workflow

```text
Create Synthetic Dataset
        ↓
Data Preparation
        ↓
Separate Features & Target
        ↓
Train/Test Split
        ↓
Random Forest Training
        ↓
Prediction
        ↓
Model Evaluation
        ↓
Save Model
        ↓
Gradio Interface
```

## 📈 Model Evaluation

The model was evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix
* Actual vs Predicted Values

The test accuracy was approximately **80%**.

## 🖥️ Gradio Interface

The project includes a Gradio interface where users can enter package information and receive a predicted damage-risk category.
![Package Damage Risk Predictor](Screenshot%202026-09-17%20001935.png)
Example inputs:

```text
Package Weight: 10 kg
Package Size: 4
Fragility Level: 5
Delivery Distance: 1200 km
Handling Points: 8
Packaging Quality: 2
Weather Risk: 1
```

Example prediction:

```text
High Damage Risk
```

## 📁 Project Files

```text
Package Damage Risk Predictor/
│
├── Package Damage Risk Predictor.ipynb
├── package_damage_model.pkl
└── README.md
```

## 🚀 How to Run

1. Open the notebook in **Google Colab**.
2. Run the cells in order.
3. Install the required libraries.
4. Train the Random Forest model.
5. Save the trained model.
6. Launch the Gradio interface.
7. Enter package information.
8. Click **Submit** to get the predicted damage risk.

## 💡 Learning Outcomes

Through this project, I practiced:

* Creating a synthetic dataset using Python
* Data handling with Pandas
* Feature and target separation
* Train/test splitting
* Random Forest classification
* Model training and prediction
* Accuracy evaluation
* Classification reports
* Confusion matrices
* Saving ML models with Joblib
* Creating a user interface with Gradio

## 👩‍💻 Author

**Zunaira Zeenat**

BS Information Technology Student

GitHub: `zunaira-zeenat`
