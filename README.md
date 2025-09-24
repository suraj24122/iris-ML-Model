# 🌸 Iris Classification Model – Training & Prediction  

This project demonstrates how to train and test a **Machine Learning model** on the famous **Iris dataset** using **Random Forest Classifier** in Python. The notebook trains a model with labeled training data and makes predictions on test samples.  

---

## 📂 Project Structure  
├── quick_training_on_iris.ipynb # Jupyter Notebook with training & predictions

├── iris_data_train.xlsx # Training dataset

├── iris_data_test.xlsx # Test dataset



---

## ⚙️ Requirements  

Make sure you have the following installed:  

- Python 3.8+  
- JupyterLab / Jupyter Notebook  
- Libraries:  
  ```bash
  pip install pandas scikit-learn openpyxl
🚀 Steps

Load the dataset

Training data → iris_data_train.xlsx

Test data → iris_data_test.xlsx

Train the Model

from sklearn.ensemble import RandomForestClassifier

model = RandomForestClassifier()
model.fit(x.values, y.values)

Make Predictions

Predict on manual input:
model.predict([[6.2, 2.5, 5.1, 1.5]])

Predict on test data:
predictions_test = model.predict(x_test.values)

🎯 Example Outputs
predictions_1
# ['Iris-virginica']

predictions_2
# ['Iris-versicolor']

📊 Model Used

Algorithm: Random Forest Classifier

Task: Multi-class classification (Iris-setosa, Iris-versicolor, Iris-virginica)

📝 Future Improvements

Add model evaluation metrics (accuracy, confusion matrix, classification report).

Try other algorithms (SVM, Logistic Regression, Decision Trees).

Deploy model using Flask / FastAPI.

🙌 Author

Developed by Suraj Singh

  
