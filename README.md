# Credit Card Fraud Detection using Random Forest Classifier

This project aims to detect fraudulent credit card transactions using a random forest classifier. The dataset used for this project is from [Kaggle], which contains transactions made by credit cards in September 2013 by European cardholders. The dataset is highly imbalanced, as only 0.172% of transactions are fraudulent.

## Dataset link:

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Installation and Usage

To run this project, you will need the following libraries:

- pandas
- numpy
- sklearn
- matplotlib
- seaborn

You can install them using pip:

```bash
pip install pandas numpy sklearn matplotlib seaborn
```

To run the project, you can use the following command:

1. After installing the dependencies, you can clone this repository to your local machine using the following command:
   ```bash
   git clone https://github.com/Muhammad-Talha4k/Credit-Card-Fraud-Detection.git

The notebook contain the code and explanation of the task.


## Results

The random forest model achieved an accuracy of 99.95%, a precision of 0.95, a recall of 0.81, an F1-score of 0.87 and Matthews correlation coefficient of 0.88 on the test set. The model was able to detect most of the fraudulent transactions, but it also had some false positives and false negatives. We use Matthews correlation coefficient to measure the quality of the binary classification, particularly when dealing with the imbalanced datasets

## Contributions

We welcome contributions from the community. Feel free to suggest improvements, fixes, or new features through issues or pull requests.
