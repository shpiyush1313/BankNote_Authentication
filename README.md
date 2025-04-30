# 💵 Bank Note Authentication using Logistic Regression

This project uses **Logistic Regression** to classify bank notes as **Authentic** or **Fake** based on features extracted from images of banknotes. The dataset includes statistical values like variance, skewness, kurtosis, and entropy.

## 📁 Files

- `Untitled32.ipynb` – Main Colab notebook for model building and evaluation.
- `banknote_authentication.csv` – Dataset from the UCI Machine Learning Repository.
- `requirements.txt` – List of required Python packages.

## 📊 Dataset


- **Features**:
  - Variance of Wavelet Transformed Image
  - Skewness of Wavelet Transformed Image
  - Kurtosis of Wavelet Transformed Image
  - Entropy of Image
- **Target**:
  - 0 = Fake
  - 1 = Authentic

## ⚙️ ML Model

- **Algorithm Used**: Logistic Regression (from `sklearn.linear_model`)
- **Steps Included**:
  - Data loading and EDA
  - Feature scaling using `RobustScaler`
  - Train-test split
  - Logistic Regression model training
  - Accuracy, classification report, and confusion matrix

## 🔍 Results

- Achieved over **97% accuracy** on the test data.
- Model performed well in identifying fake vs authentic notes.



## 📦 Requirements

See the `requirements.txt` for dependencies.

## 👨‍💻 Author

Piyush Sharma  
Feel free to connect for feedback or improvements!
