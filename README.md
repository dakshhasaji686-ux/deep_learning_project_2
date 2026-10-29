# Adult Income Prediction Using Deep Learning

## Project Overview
This project uses an Artificial Neural Network (ANN) to predict whether a person's annual income is above $50,000 based on demographic and employment-related information.

## explanation video of the project
https://drive.google.com/file/d/19rvRA38l0Q5Vo41xpakljM5yYj-Df7xT/view?usp=sharing

## Dataset
- **Name:** Adult Income Dataset
- **Source:** [Kaggle – Adult Income Dataset](https://www.kaggle.com/datasets/wenruliu/adult-income-dataset)
- **Target:** `income`
- `0` = Income ≤ $50K
- `1` = Income > $50K

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- TensorFlow / Keras
- Google Colab

## Project Steps
1. Data loading and cleaning
2. Exploratory Data Analysis (EDA)
3. Categorical encoding and feature scaling
4. Baseline ANN development
5. Activation function comparison
6. Weight initialization experiments
7. Loss function comparison
8. Batch Normalization
9. Regularization techniques
10. Hyperparameter tuning
11. Model evaluation and comparison

## Best Results

The tanh activation model achieved the highest F1-score among the evaluated models.

| Metric | Score |
|---|---:|
| Accuracy | 84.71% |
| Precision | 69.69% |
| Recall | 67.80% |
| F1-score | 0.6873 |
| ROC-AUC | 0.9028 |

## How to Run
1. Download the dataset from Kaggle.
2. Open the notebook in Google Colab.
3. Upload `adult.csv`.
4. Run the notebook cells in order.
5. Review the model comparisons and evaluation metrics.

## Conclusion
This project explores different ANN techniques and compares their performance on an imbalanced classification dataset. It demonstrates how activation functions, loss functions, initialization, normalization, and regularization affect model performance.

## Author
Daksh Hasaji
