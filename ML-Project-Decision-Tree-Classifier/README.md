# Titanic Survival Prediction – Decision Tree Classifier

## Project Overview
This project uses Machine Learning to predict whether a passenger survived the Titanic disaster. A Decision Tree Classifier is trained using passenger information to perform binary classification.

## Objective
To build and evaluate a Decision Tree classification model that predicts passenger survival based on selected features.

## Dataset
- **Dataset:** Titanic Train Dataset (`train.csv`)
- **Target Variable:** `Survived`
- **Selected Features:**
  - `Pclass` – Passenger class
  - `Sex` – Passenger gender
  - `Age` – Passenger age
  - `Fare` – Ticket fare

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Data Preprocessing
- Handled missing values in the `Age` column using median imputation.
- Converted the `Sex` column into numerical values using Label Encoding.
- Split the dataset into training and testing sets using an 80:20 ratio.

## Model Development
A Decision Tree Classifier was implemented with the following configuration:

- **Criterion:** Gini
- **Maximum Depth:** 4
- **Random State:** 42

## Model Evaluation

| Evaluation Metric | Result |
|---|---:|
| Model Accuracy | 79.89% |
| Baseline Accuracy | 58% |
| Tree Depth | 4 |
| Number of Leaves | 15 |
| Root Attribute | Sex |

### Confusion Matrix
```text
[[92 13]
 [23 51]]
```

The model achieved 79.89% accuracy on the test dataset, performing better than the baseline prediction.

## Feature Importance
Feature importance was extracted using the Decision Tree model's `feature_importances_` attribute to examine the contribution of the selected features to its predictions.

## Limitation
The model uses only four features and does not consider other potentially useful information, such as family size and embarkation port. This may limit its ability to capture all factors associated with passenger survival.

## Project Structure
```text
ML-Project-Decision-Tree-Classifier/
│
├── ML Project.ipynb
└── README.md
```

## Conclusion
This project demonstrates the application of a Decision Tree Classifier to a real-world binary classification problem. The model achieved 79.89% test accuracy and performed better than the baseline classifier.
