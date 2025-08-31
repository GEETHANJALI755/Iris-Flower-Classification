# 🌸 Iris Flower Classification Project

## 📌 Objective  
Classify iris flowers into three species (**Setosa**, **Versicolor**, **Virginica**) based on sepal and petal measurements using Machine Learning.

---

## 📊 Dataset  
- **Source**: [Scikit-learn Iris Dataset](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html)  
- **Features**:  
  - Sepal Length (cm)  
  - Sepal Width (cm)  
  - Petal Length (cm)  
  - Petal Width (cm)  
- **Target Classes**:  
  - Setosa  
  - Versicolor  
  - Virginica  

---

## 🚀 Steps Implemented  
1. **Load & explore dataset** (Iris dataset from scikit-learn)  
2. **Split into training/testing sets**  
3. **Train a Logistic Regression model**  
4. **Evaluate performance** with classification report and confusion matrix  
5. **Predict custom user input** (interactive flower prediction)  
6. **Visualize results**: scatter plot, confusion matrix heatmap, and decision boundaries  
7. **Save trained model** (`iris_model.pkl`) for future use  

---

## 📈 Visualizations  

### 🌿 Dataset Scatter Plot  
Sepal Length vs Petal Length colored by species.  
![Scatter Plot](images/scatter_plot.png)

### 📉 Confusion Matrix  
Heatmap showing classifier performance.  
![Confusion Matrix](images/confusion_matrix.png)

### 🔮 Decision Boundary  
Model decision regions using Logistic Regression (first two features).  
![Decision Boundary](images/decision_boundary.png)

---

## 🧮 Model Performance  
Example evaluation (values may vary depending on train/test split):  

```
              precision    recall  f1-score   support

     setosa       1.00      1.00      1.00        10
 versicolor       1.00      0.90      0.95        10
  virginica       0.91      1.00      0.95        10

    accuracy                           0.97        30
   macro avg       0.97      0.97      0.97        30
weighted avg       0.97      0.97      0.97        30
```

---

## ▶️ How to Run  

### 🔹 1. Clone Repository  
```bash
git clone https://github.com/your-username/Iris-Flower-Classification.git
cd Iris-Flower-Classification
```

### 🔹 2. Install Requirements  
```bash
pip install -r requirements.txt
```

### 🔹 3. Run Script  
```bash
python iris_classification.py
```

### 🔹 4. Predict Custom Input  
Example:  
```
Enter sepal length (cm): 5.1  
Enter sepal width (cm): 3.5  
Enter petal length (cm): 1.4  
Enter petal width (cm): 0.2  

✅ Predicted flower type: setosa
```

---

## 📂 Project Structure  
```
Iris-Flower-Classification/
│── images/                  # Plots (scatter, confusion matrix, decision boundaries)
│── iris_classification.py   # Main project code
│── requirements.txt         # Python dependencies
│── README.md                # Documentation
```

---

## 🛠️ Tech Stack  
- **Python**  
- **NumPy, Pandas**  
- **Matplotlib, Seaborn**  
- **Scikit-learn**  
- **Joblib (for model saving)**  

---

## ✅ Skills Gained  
- Data loading & exploration  
- Train/Test splitting  
- Logistic Regression classification  
- Model evaluation & visualization  
- Custom input predictions  
- Saving/loading trained models  

---

## 🌟 Author  
📌 *Your Name*  
💡 Beginner ML Project | GitHub Portfolio Showcase
