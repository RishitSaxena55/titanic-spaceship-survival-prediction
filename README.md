# 🛸 Spaceship Titanic - Survival Prediction

This repository presents a machine learning solution to predict which passengers were transported to another dimension in the fictional Spaceship Titanic disaster. This project is based on the [Kaggle Spaceship Titanic competition](https://www.kaggle.com/competitions/spaceship-titanic).

---

## 📁 Files

- `titanic-spaceship-survival.ipynb` – Main Jupyter Notebook with complete code.
- `train.csv` – Training data with features and target (`Transported`).
- `test.csv` – Test data without labels, used for prediction.
- `README.md` – Project documentation.

---

## 🎯 Objective

To build and compare multiple machine learning models that can accurately classify whether a passenger was `Transported` (i.e., teleported to another dimension).

---

## 🧠 Machine Learning Models Used

- **Decision Tree Classifier**
- **Random Forest Classifier**
- **XGBoost Classifier**

All models are evaluated using accuracy on the validation dataset.

---

## 🗃️ Dataset Overview

The dataset includes information on ~8,700 passengers. Each row represents one passenger.

### 📌 Target Variable
- `Transported`: Boolean — Whether the passenger was transported to another dimension (`True` or `False`)

### 📌 Feature Descriptions

| Feature         | Description |
|----------------|-------------|
| `PassengerId`   | Unique ID for each passenger |
| `HomePlanet`    | Planet the passenger departed from |
| `CryoSleep`     | Whether the passenger elected to be put into cryosleep |
| `Cabin`         | Cabin number (Deck/Num/Side) |
| `Destination`   | Destination of the passenger |
| `Age`           | Age of the passenger |
| `VIP`           | Whether the passenger paid for special VIP service |
| `RoomService`   | Amount spent on room service |
| `FoodCourt`     | Amount spent on the food court |
| `ShoppingMall`  | Amount spent in the shopping mall |
| `Spa`           | Amount spent at the spa |
| `VRDeck`        | Amount spent on the virtual reality deck |
| `Name`          | Name of the passenger |

---

## 🔧 Workflow

1. Load `train.csv` and `test.csv` files
2. Clean and preprocess data:
   - Handle missing values
   - Encode categorical features
3. Feature selection
4. Split data into training and validation sets
5. Train and evaluate models
6. Compare performance using `accuracy_score`

---
