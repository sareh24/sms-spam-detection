# SMS Spam Detection Machine Learning Project

A machine learning project to classify SMS messages as spam or ham using Natural Language Processing techniques.

## 📋 Overview

This project implements a spam detection system using:
- **Dataset**: SMS Spam Collection Dataset (5,572 messages)
- **Model**: Multinomial Naive Bayes Classifier
- **Feature Extraction**: TF-IDF Vectorization
- **Accuracy**: 97.22%

## 📁 Files

- `spam_detection.ipynb` - Main Jupyter notebook with complete analysis and outputs
- `spam.csv` - Dataset file containing SMS messages labeled as spam or ham

## 🔍 Project Steps

1. Dataset loading and exploration
2. Data preprocessing and visualization
3. Feature extraction using TF-IDF
4. Model training (Naive Bayes)
5. Model evaluation and testing
6. Sample predictions

## 📊 Results

The model achieves the following performance metrics:

| Metric | Ham | Spam |
|--------|-----|------|
| **Precision** | 0.97 | 0.99 |
| **Recall** | 1.00 | 0.80 |
| **F1-Score** | 0.98 | 0.88 |

**Overall Accuracy**: 97.22%

## 🛠️ Requirements

Install the required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Or install using requirements.txt (if you create one):
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## 🚀 Usage

1. Clone this repository:
```bash
git clone <repository-url>
cd <repository-name>
```

2. Open the notebook:
   - **Jupyter Notebook**: `jupyter notebook spam_detection.ipynb`
   - **Google Colab**: Upload `spam_detection.ipynb` and `spam.csv` to Colab

3. Make sure `spam.csv` is in the same directory as the notebook

## 📝 Note

The notebook contains pre-executed cells with all outputs. You can run the cells to regenerate the results or simply view the existing outputs.

