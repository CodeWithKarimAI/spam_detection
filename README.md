# spam_detection
ML model to classify SMS messages as Spam or Ham using NLP

## Features

* Text cleaning and preprocessing
* Stopwords removal and lemmatization
* TF-IDF feature extraction
* Model training using:

  * Logistic Regression
  * Support Vector Machine (SVM)
  * Naive Bayes
* Model comparison based on accuracy
* Confusion matrix visualization
* Prediction function for new messages

## Technologies

* Python
* Pandas
* NLTK
* Scikit-learn
* Matplotlib
* Seaborn

## Workflow

1. Load dataset
2. Clean and preprocess text
3. Encode labels
4. Split data into training and testing sets
5. Train multiple models
6. Evaluate performance
7. Select best model
8. Predict new messages

## Example

```python
predict_message("Congratulations! You won a free ticket")
```

Output:

```
Spam
```

## Notes

Simple project for practice, might improve it later.

## Author
Karim Ahmed - CodeWithKarimAI

