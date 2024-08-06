# Emotion Classification in Text Using Machine Learning

This project aims to classify emotions in text samples using various machine learning models. The dataset consists of text data labeled with different emotions. The project involves preprocessing the text data, feature extraction, model training, and evaluation.

## Dataset

The dataset used in this project contains text samples along with their corresponding emotion labels. It can be found here. 
https://drive.google.com/file/d/1HWczIICsMpaL8EJyu48ZvRFcXx3_pcnb/view?usp=drive_link

## Preprocessing

The preprocessing steps involve:

*Lowercasing*:  Convert all text to lowercase to ensure consistent representation.

*Text Cleaning*:  Removing special characters, numbers, and extra spaces.

*Tokenization:*  Splitting text into words.

*Stopword Removal*:  Removing common English stopwords.

*Lemmatization*:  This reduces words to their base or dictionary form, known as the lemma.

## Feature Extraction

We use TfidfVectorizer to transform the cleaned text data into numerical features. This method converts text into a matrix of TF-IDF features, which are then used as inputs for machine learning models.

## Model Development

The following models were trained and evaluated:

*Naive Bayes*:  A probabilistic classifier based on Bayes' theorem.

*Support Vector Machine (SVM)*:  A robust classifier that finds the optimal hyperplane separating different classes.

## Evaluation

We evaluate the models using the following metrics:

*Accuracy*:  The proportion of correct predictions.

*F1-Score*:  The harmonic mean of precision and recall.

## Results
### Naive Bayes:

Accuracy:  0.9082

F1 Score:  0.9082

### SVM:

Accuracy:  0.9419

F1 Score:  0.9419

The SVM model outperformed the Naive Bayes model in both accuracy and F1-score.

## Conclusion

Both models are suitable for emotion classification in text. Naive Bayes offers a quick and straightforward approach, while SVM provides more flexibility and robustness, potentially leading to better performance. In this case, the SVM model has slightly higher accuracy and F1-score, indicating that it performs better on the given dataset. However, the choice between the two may also depend on the specific requirements, such as computational resources and the need for interpretability.
