# Titanic Survival Prediction 🚢

This project applies machine learning models to predict whether a passenger survived the Titanic disaster based on various features. The dataset includes attributes like age, gender, ticket class, and more.

## 📌 Project Structure
Titanic-Survival-Prediction/ │── data/ # Directory for dataset │── models/ # Directory for saved models (optional) │── notebooks/ # Jupyter notebooks for EDA & analysis │── src/ # Source code for preprocessing & modeling │ ├── preprocess.py # Data preprocessing pipeline │ ├── train.py # Model training & evaluation │── README.md # Project documentation │── requirements.txt # Dependencies │── main.py # Main script to run the model │── Titanic_Survival.ipynb # Jupyter Notebook with EDA & ML Models

## 🚀 Features
- **Data Preprocessing**  
  - Extract surnames from names  
  - Split ticket into numeric & categorical  
  - Handle missing values  
  - Standardize numerical features  
  - Encode categorical features  

- **Machine Learning Models**
  - Linear SVM
  - Decision Tree
  - Random Forest
  - Gradient Boosting  

- **Performance Evaluation**
  - Accuracy Score  
  - R² Score  
  - Confusion Matrix  
  - Classification Report  

## 📊 Dataset
The dataset includes:  
- **Categorical Features**: Sex, Embarked, Ticket  
- **Numerical Features**: Age, Fare, Pclass  
- **Target Variable**: Survived (0 = No, 1 = Yes)  

## 🛠️ Installation

1️⃣ Clone the repository  
```bash
git clone https://github.com/salman1451/Titanic-Survival-Prediction.git
cd Titanic-Survival-Prediction
pip install -r requirements.txt
python main.py

Let me know if you need any changes! 🚀
