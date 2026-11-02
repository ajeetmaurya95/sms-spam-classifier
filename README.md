# SMS Spam Classifier

A machine learning model that reads an SMS and tells whether it is spam or a normal message.

## Dataset
SMS Spam Collection (UCI Machine Learning), 5,572 messages: 4,825 normal and 747 spam.

## How it works
1. Load the data with pandas and label messages as 0 (normal) or 1 (spam).
2. Convert text to numbers using TF-IDF.
3. Split the data: 80% training, 20% testing.
4. Train a Multinomial Naive Bayes model.
5. Test it on messages the model has never seen.

## Result
Accuracy on the test set: about 96.7%.

## Limitations
- The model learned only from English messages, so it can be wrong on Hinglish or other languages.
- Spam messages are fewer than normal ones in the data, so accuracy alone does not tell the full story.

## Tools
Python, pandas, scikit-learn, Google Colab

## Author
Ajeet Maurya, B.Tech CSE (AI)
