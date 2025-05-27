# 🎓 School Dropout Prediction using Machine Learning

This project uses a supervised learning approach to predict whether a student is likely to drop out of school based on multiple socio-economic and academic features.

## 📊 Objective

Predict student dropout using a binary classification model to assist educational institutions in taking early intervention measures.

## 🔧 Technologies Used

- Python
- NumPy, Pandas
- TensorFlow / Keras
- Scikit-learn
- Matplotlib
- SMOTE (for class balancing)

## 🧠 Machine Learning Pipeline

1. **Data Loading**: Handled `.npz` files containing training and test data
2. **Preprocessing**: Ensured correct data types, balanced classes using SMOTE
3. **Modeling**: Trained a deep learning model using TensorFlow with:
   - Dense hidden layers
   - Binary output layer with sigmoid activation
   - EarlyStopping to prevent overfitting
4. **Evaluation**: Validated on a hold-out set and monitored accuracy + loss
5. **Export**: Saved final predictions to CSV for dashboard integration (e.g., Tableau)

## 📁 Project Structure

school-dropout-prediction/
├── dropout_model.ipynb # Main training + prediction notebook
├── school_dropout_data_train.npz
├── school_dropout_data_test.npz
├── test_with_predictions.csv # Output predictions for Tableau
└── README.md

## 📈 Sample Output

- Accuracy: 86%
- F1 Score: 0.78
- Final output: CSV with predictions for dashboarding in Tableau

## ✅ What This Shows

✔️ Real-world ML workflow  
✔️ Data preprocessing and imbalance handling  
✔️ Use of TensorFlow for practical problems  
✔️ Output generation for BI tools
