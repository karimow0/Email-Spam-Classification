Email Spam Classification (Naive Bayes)

This is a student project where I built a spam classifier using the Naive Bayes algorithm and Python. The goal is to detect whether a given message is spam or ham (not spam).

Dataset
I used a dataset called SMSSpamCollection.tsv, which contains around 5500 messages. Each message has a label (spam or ham) and the message text.
Example:

spam   goldviking (29/M) is inviting you to be his friend. ...
ham    Dont let studying stress you out.
ham    That's y u haf 2 keep me busy...



What the Code Does???
Loads and explores the dataset
Cleans the text (removes numbers, punctuation, etc.)
Converts labels (spam/ham) to numbers
Transforms the text into numerical features using TF-IDF
Splits data into training and testing sets
Trains a Multinomial Naive Bayes model
Predicts new messages and shows accuracy
Visualizes spam vs ham counts
Shows distribution of message lengths
Example Prediction
The model can predict if a message like
"Congratulations! You've won a lottery!"
is spam or not.