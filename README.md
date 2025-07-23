# 🌸 Iris Flower Classification

This project is a beginner-friendly machine learning model that classifies iris flower species using Random Forest Classifier. It uses the popular Iris dataset containing measurements of different flower species.

---

## 📁 Dataset Information

- **File:** `Iris.csv`
- **Features:**
  - SepalLengthCm
  - SepalWidthCm
  - PetalLengthCm
  - PetalWidthCm
- **Target:**
  - Species (Setosa, Versicolor, Virginica)

---

## 🔧 Libraries Used

- `pandas` – for data handling  
- `seaborn` / `matplotlib` – for data visualization  
- `sklearn` – for preprocessing, model building, and evaluation

---

## 🧪 Steps Performed

1. **Load Data:** Used `pandas.read_csv()` to load the dataset.
2. **Drop Unnecessary Columns:** Removed `Id` column.
3. **Data Preprocessing:** 
   - Feature-target split (`X` and `y`)
   - Standardization using `StandardScaler`
4. **Train-Test Split:** 
   - 80% training and 20% testing using `train_test_split`
5. **Model Building:**
   - Used `RandomForestClassifier` with `n_estimators=100`
6. **Prediction:** Predicted the classes using the trained model.
7. **Evaluation:**
   - Achieved **100% accuracy**
   - Confusion matrix & classification report added

---

## 📊 Model Accuracy

```python
Accuracy: 100.00%
