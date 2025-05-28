# 🩺 Diabetes Prediction using Machine Learning

This project involves predicting diabetes progression using regression models trained on the diabetes dataset from Scikit-learn. The focus is on applying machine learning techniques and hyperparameter tuning to optimize model performance.

## 📊 Dataset

- **Source:** `sklearn.datasets.load_diabetes()`
- **Samples:** 442
- **Features:**
  - `age`, `sex`, `bmi`, `bp`, `s1`, `s2`, `s3`, `s4`, `s5`, `s6`
- **Target:** A quantitative measure of disease progression one year after baseline.

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Pickle (for model serialization)
- Google Colab

## 🚀 Workflow

1. Load the diabetes dataset using `load_diabetes()`.
2. Convert to DataFrame and prepare features and labels.
3. Apply multiple regression models.
4. Tune hyperparameters using techniques such as GridSearchCV.
5. Evaluate model performance using metrics like R² score and Mean Squared Error (MSE).
6. Save and load models using `pickle`.

## 📈 Models Considered

- Decision Tree Regressor

## 🔧 Hyperparameter Tuning

Hyperparameter tuning was performed using:
- `GridSearchCV` or manual testing of parameter combinations.

## 📌 Results

| Model                  | R² Score / MSE (Example) |
|------------------------|--------------------------|
| Decision Tree Regressor      | 0.88                    



## 📂 Project Structure

Diabetes_Prediction/
├── Diabetes_Prediction.ipynb # Main notebook
├── model.pkl # Saved model (if applicable)
├── README.md # Project description
