# Heart Disease Prediction with an ANN

Binary classification of heart disease using a fully-connected neural network (TensorFlow/Keras).
Coursework, November 2023.

## Contents
| File | Description |
|---|---|
| `11_19_assignments_of_heart_rate.ipynb` | Preprocessing, standardization, ANN training and evaluation |
| `heart.csv` | UCI heart disease data: 13 clinical features (age, sex, cholesterol, max heart rate, …) and a 0/1 `target` |
| `11_25_set_theory_assignment.ipynb` | pandas DataFrame practice (separate assignment) |

## Approach
1. Load `heart.csv` and check feature types and the target balance.
2. Train/test split and `StandardScaler` standardization.
3. Train a `Sequential` model of `Dense` layers with a sigmoid output.
4. Evaluate accuracy on the held-out test set.

## Run
Open the notebook in Google Colab with the badge at the top of the file.
