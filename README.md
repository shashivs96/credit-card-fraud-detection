# Credit Card Fraud Detection 

This project aims to detect fraudulent credit card transactions using a supervised machine learning approach. Since the dataset is highly imbalanced, SMOTE (Synthetic Minority Oversampling Technique) is used to balance the classes before training.

## 📁 Project Structure

- `credit_card_fraud_detection.ipynb`: Jupyter notebook containing the complete pipeline — from data loading and preprocessing to model training, class balancing with SMOTE, and evaluation.

## 📊 Dataset

- Contains 11665 transactions made by European cardholders in September 2013.
- Only 49 transactions are labeled as fraud (\~0.42%), making it a highly imbalanced dataset.
- Features are numerical and result from a PCA transformation, except for `Time` and `Amount`.

## ⚙️ Tools & Libraries

- Google Colab (Python)
- `pandas`, `numpy`
- `scikit-learn`
- `imbalanced-learn` (SMOTE)
- `matplotlib`, `seaborn`

## 🧠 Model

- **Algorithm**: Decision Tree, Random forest
- **Class Balancing**: SMOTE used to oversample the minority class (fraudulent transactions)
- **Preprocessing**:
  - Feature scaling
  - Train-test split before applying SMOTE

## 📈 Evaluation Metrics

- **Confusion Matrix** to visualize prediction results
- **Precision**, **Recall**, and **F1-score**
- Emphasis on **Recall** to minimize false negatives (missed fraud cases)

## ✅ Future Work

- Experiment with advanced models (Random Forest, XGBoost, Neural Networks)
- Implement cross-validation for more robust model validation
- Explore real-time fraud detection simulation
- Hyperparameter tuning for improved performance

## 📌 Disclaimer

This project is for educational and research purposes only. The dataset is publicly available and fully anonymized.
