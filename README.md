# NBC-RottenTomatoesaReview
This NBC (Naive Bayes Classifier) is a simple text classification algorithm that is based on Bayes' theorem. It is particularly useful for text classification tasks, such as spam detection, sentiment analysis, and topic categorization. This classifier uses a "naive" assumption that the features (words) are independent of each other, which allows it to be trained quickly and effectively.

Prerequisites
In order to use this classifier, you will need:

Jupyter Notebook (version 5.7.8 or higher)
Python (version 3.5 or higher)
pandas (version 0.23.4 or higher)
numpy (version 1.15.4 or higher)
scikit-learn (version 0.20.1 or higher)

pip install jupyter pandas numpy scikit-learn

To use this classifier, you can follow these steps:

Clone this repository to your local machine.
Open Jupyter Notebook and navigate to the cloned repository.
Open the NBC.ipynb file.
Run the code cells in the notebook to train and test the classifier.
Modify the code as necessary to fit your specific use case.

The NBC algorithm works as follows:

Convert the training documents into a bag-of-words representation.
Calculate the class prior probabilities.
For each word in the vocabulary:
Calculate the conditional probability of the word given each class.
To classify a new document:
Convert the document into a bag-of-words representation.
Calculate the class posterior probabilities using Bayes' theorem.
Choose the class with the highest probability as the predicted class.

The NBC classifier is a simple yet effective algorithm for text classification tasks. It is easy to implement and can achieve good results with relatively little training data. This classifier can be further optimized by using techniques such as feature selection, smoothing, and parameter tuning.
