
# Stroke Prediction Models and Data Analysis

This repository presents an in-depth analysis of stroke prediction, encompassing data cleaning, exploratory data analysis (EDA), and model training and evaluation.

## Data Cleaning and Exploratory Data Analysis (EDA)

We began by thoroughly cleaning the dataset, addressing missing values, outliers, and inconsistencies. Following this, we conducted exploratory data analysis to gain insights into the dataset's characteristics and relationships between variables. Visualizations and statistical summaries were utilized to comprehend the data's distribution and patterns.

## Model Training and Evaluation

### SMOTE (Synthetic Minority Over-sampling Technique)

We employed SMOTE to address class imbalance, ensuring robust model performance in predicting stroke occurrences.

### Model Training

We trained a variety of classification models on a split of 80-20. The models included:
- Random Forest (RF)
- Naive Bayes (NB)
- Logistic Regression (LR)
- Ridge Classifier (RC)
- K-Nearest Neighbors (KNN)
- Decision Trees
- ExtraTrees
- XGBoost (XGB)
- LightGBM (LGBM)
- CatBoost
- Bagging Classifier

### Evaluation Metrics

Each model was evaluated using a range of metrics including accuracy, precision, recall, F1-score, and ROC-AUC. These metrics provide a comprehensive understanding of each model's performance and their suitability for stroke prediction.

## Conclusion

After thorough analysis and evaluation, we derived insights into the effectiveness of different classification models in predicting strokes. The conclusion sheds light on the most promising models and highlights areas for further improvement.

## Usage

1. Clone the repository:
   ```
   git clone https://github.com/deepak22s/brainstroke-prediction-using-ML.git
   ```

2. Navigate to the cloned directory:
   ```
   cd stroke-prediction-analysis
   ```

3. Follow the provided Jupyter notebooks or scripts to replicate the analysis and explore the models.

## Contributions

Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
