
This project includes Natural Language Processing and the Machine Learning practices.

# Review-Recommendation-Prediction
This project's aim is to build a machine learning model that reads a shopping review and predicts if the customer is recommending the product or not. Machine Learning and Natural Language Processing methods will be used to achieve this.

# Comparison between Count Vectorizing and TF-IDF Vectorizing and the results

Vectorization | Accuracy
------------ | -------------
Count | 86.1%
TF-IDF | 85.6%


# Data Used
The model was built using [data found on Kaggle](https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews).


# Libraries Used
```
pandas
numpy
string
re
nltk
sklearn
warnings
time
```

# Author
- Koray Çağlar - [koraycaglar](https://github.com/koraycaglar)

# Further Notes
GridSearch Cross-Validation can be used to optimize the hyperparameters of the model but my RAM couldn't take it.

# Files

- Code_notebook includes the code for:
     - Null value handling
     - Removing punctiations
     - Tokenizing
     - Removing stopwords
     - Lemmatizing
     - Vectorizing
     - Model building and final results

- data.csv file includes the data used during this project
