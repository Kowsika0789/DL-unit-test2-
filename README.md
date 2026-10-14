# Language Identification Using LSTM

## About the Project

This project identifies the language of a given text using a deep learning model based on Long Short-Term Memory (LSTM). It classifies text into 22 different languages using character-level patterns.

The model was developed using Python, TensorFlow and Keras in Google Colab.

## Dataset

The dataset was obtained from Kaggle.

Dataset link: https://www.kaggle.com/datasets/zarajamshaid/language-identification-datasst

It contains text samples and their corresponding language labels. Up to 500 samples per language were selected for this project.

## Technologies Used

- Python
- TensorFlow and Keras
- Pandas and NumPy
- Scikit-learn
- Matplotlib and Seaborn
- Google Colab

## Methodology

1. Cleaned the dataset by removing missing values, empty records and duplicates.
2. Selected samples from 22 languages.
3. Split the data into 70% training, 15% validation and 15% testing.
4. Converted text into character sequences using tokenization.
5. Applied padding to make each sequence 300 characters long.
6. Built an LSTM model with two LSTM layers, dropout and dense layers.
7. Trained the model using the Adam optimizer.
8. Evaluated the model using accuracy, precision, recall and F1-score.
9. Generated graphs and a confusion matrix to analyze performance.
10. Implemented manual text input to predict the language.

## Model Performance

| Metric | Score |
|---|---:|
| Test Accuracy | 82.67% |
| Macro Precision | 0.8507 |
| Macro Recall | 0.8267 |
| Macro F1-Score | 0.8139 |

## Visualizations

The project includes training and validation accuracy graphs, loss graphs, a confusion matrix, and language-wise performance comparisons.

## How to Run

1. Download the dataset from Kaggle.
2. Open the notebook in Google Colab.
3. Upload `dataset.csv`.
4. Run the notebook cells in order to preprocess the data, train the model, evaluate its performance and predict languages for new text.

## Future Improvements

- Improve accuracy for languages with lower performance.
- Experiment with different model architectures.
- Develop a simple web application for language identification.

## Author

Developed as a deep learning project in Natural Language Processing.
