# spam_detection
To detect whether the given message is spam or ham.
### Steps
1. Import libraries
2. Import data
3. Data Cleaning
4. Exploratry Data Analysis
5. Splitting data
6. Model Building
* Data contains 5 columns, whether the message is spam or ham, message, 3 unnamed columns.
* Removed 3 unnamed columns, since 95% of values in these column contain null values.
* map spam to 1, ham to 0
* using sentence tokenizer and word tokenizer , created column for number of words, number of sentences
* a new clumn for number of character sin each message
* creating histograms for number of words, type tells us as the number of words increases spam increases.
* In the similar way for number of sentences and number of characters.
* TF-IDF vectorization for transforming text into maningful representation of numbers, which is used to fit machine learning algorithm for prediction.
* Here we are predicting either it is  a spam or ham, it is  a binary classification problem.
* in this we used models Logistic Regression, XGBoost, KNN, Decison Tree, RandomForestClassifier
* We got good score for xgboost among other models.
.  We will use model for prediction.
