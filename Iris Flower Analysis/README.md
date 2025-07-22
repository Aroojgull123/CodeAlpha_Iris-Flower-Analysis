# 🌸 Iris Flower Classification and Data Visualization

This project focuses on analyzing and classifying Iris flower species using basic data analysis techniques and machine learning models in Python.

## 📌 Objective

- Analyze the Iris dataset (Setosa, Versicolor, Virginica)
- Visualize relationships between flower measurements (sepal & petal)
- Train a machine learning model to classify the flower species
- Evaluate model performance using accuracy and classification metrics

---

## 📊 Dataset

- **Name:** Iris Dataset  
- **Source:** Built-in dataset available via `seaborn` and `scikit-learn`
- **Features:**
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- **Target:** Species (`setosa`, `versicolor`, `virginica`)

---

## 🛠️ Tools & Libraries Used

- `pandas` – Data handling
- `matplotlib` & `seaborn` – Data visualization
- `scikit-learn` – Model training and evaluation

---

## 📈 Exploratory Data Analysis (EDA)

- Displayed dataset structure using `.shape`, `.columns`, `.head()`
- Created visualizations:
  - **Boxplots** for each feature by species
  - **Pairplot** to understand feature relationships
  - **Histograms** for distribution

---

## 🤖 Machine Learning Model

- **Model Used:** Logistic Regression
- **Data Preparation:**
  - Features (`X`) = flower measurements
  - Target (`y`) = flower species (encoded)
  - Train/Test Split = 80/20
- **Evaluation Metrics:**
  - Accuracy: **100%**
  - Classification Report (Precision, Recall, F1-score)
  - Confusion Matrix (optional)

---

## ✅ Results

- The model achieved **perfect classification accuracy (1.0)** on the test set.
- All species were correctly predicted using just the 4 numeric features.
- Visual analysis showed clear separability between classes, especially with petal features.

---


