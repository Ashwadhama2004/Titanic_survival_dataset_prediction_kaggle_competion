# Titanic_survival_dataset_prediction_kaggle_competion

```markdown
# 🚢 Titanic Survival Prediction 🌊

Welcome to the **Titanic Survival Prediction** project! 🌟 In this project, we’re diving into the famous Titanic dataset 🛳️ to predict whether a passenger would survive or not. Using some awesome machine learning algorithms, we’ll find out who would have made it and who wouldn’t. Let's go on this data adventure!

![Titanic Image](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fd/RMS_Titanic_3.jpg/1920px-RMS_Titanic_3.jpg)

---

## 💼 Project Overview

We used data from [Kaggle's Titanic Dataset](https://www.kaggle.com/c/titanic/data), which contains a bunch of cool features like age, ticket class, and even fare. By applying machine learning models, we’ll predict if a passenger survived based on these features.

### 📊 Dataset Features

- **PassengerId**: Unique ID for each passenger.
- **Survived**: 0 = No, 1 = Yes.
- **Pclass**: Passenger’s class (1st, 2nd, or 3rd).
- **Name**: Passenger's full name.
- **Sex**: Male or Female.
- **Age**: Passenger's age.
- **SibSp**: Number of siblings/spouses aboard.
- **Parch**: Number of parents/children aboard.
- **Ticket**: Ticket number.
- **Fare**: Amount paid for the ticket.
- **Embarked**: Port of departure (C = Cherbourg, Q = Queenstown, S = Southampton).

### 🛠️ Handling Missing Data

- **Age**: Replaced missing values with the average age.
- **Embarked**: Filled missing values with the most common port (mode).
- **Cabin**: Dropped because it had too many missing values.

---

## 🔮 Models Used

We experimented with three cool machine learning models to predict survival:

1. **🧮 Logistic Regression**: Simple yet effective.
   - Accuracy: **~80%** on training data and **~79%** on test data.

2. **🌲 Random Forest Classifier**: A powerful ensemble of decision trees!
   - Accuracy: **~98%** on training data and **~82%** on test data.

3. **🚀 XGBoost**: Super-fast gradient boosting algorithm.
   - Accuracy: **~98.5%** on training data and **~83%** on test data.

Want to improve? Play around with model tuning and try out other algorithms like Gradient Boosting, SVM, or even Neural Networks!

---

## 🚀 How to Run the Project

Ready to make some predictions? Follow these steps!

### Prerequisites

You’ll need a few Python libraries to run this project. Install them easily with pip:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn xgboost
```

### Step-by-Step Guide

1. **Clone the Repo**: Get a copy of this project on your local machine:

```bash
git clone https://github.com/Ashwadhama2004/titanic-survival-prediction.git
cd titanic-survival-prediction
```

2. **Get the Dataset**: Download the Titanic dataset from [Kaggle](https://www.kaggle.com/c/titanic/data) and place it in the project folder.

3. **Run the Notebook**: Fire up your Jupyter Notebook and start the magic:

```bash
jupyter notebook titanic_survival_prediction.ipynb
```

Or you can run the Python script directly if you're in a hurry! 🏃‍♂️

---

## 📈 Results

Here’s how our models stacked up:

- **Logistic Regression**: Test Accuracy = **79.88%**
- **Random Forest Classifier**: Test Accuracy = **82.12%**
- **XGBoost**: Test Accuracy = **83%**

But wait! There’s more to explore. You can make the models even better with some hyperparameter tuning and feature engineering. 🚀

---

## 💡 Future Enhancements

Here's what you can do to push this project further:
- **⚙️ Hyperparameter Tuning**: Fine-tune model settings for even better results.
- **💡 Feature Engineering**: Add or modify features to improve prediction accuracy.
- **🧠 Try More Models**: Experiment with Gradient Boosting, Neural Networks, or other fancy models.

---

## 🛠️ Tech Stack

Here’s what we used to build this project:

- **Language**: Python 🐍
- **Libraries**: `numpy`, `pandas`, `scikit-learn`, `matplotlib`, `seaborn`, `xgboost`
- **Jupyter Notebook**: For interactive data exploration and model training.

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## 👋 Connect with Me

If you enjoyed this project or have any questions, feel free to reach out!

- GitHub: [Ashwadhama2004](https://github.com/Ashwadhama2004)

---

Thanks for checking out my Titanic Survival Prediction project! Hope you enjoy exploring the data and building models as much as I did! 😊
```
