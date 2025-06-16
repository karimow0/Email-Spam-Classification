📧Email Spam Classifier

This project uses Python and machine learning to classify SMS messages as Spam or Ham (not spam). The model is trained on a real-world dataset using TF-IDF features and a Naive Bayes classifier.

📁Dataset
File: SMSSpamCollection.tsv
Format: Tab-separated (.tsv)
Contains 5,572 SMS messages
Columns:
label: spam or ham
text: the message content

🛠️ Technologies Used
Python
Jupyter Notebook
pandas, scikit-learn, matplotlib, seaborn
Machine Learning: Naive Bayes
NLP preprocessing (lowercasing, punctuation & digit removal, TF-IDF)
📊 Steps Performed
Data Loading
Text Cleaning
Label Encoding
TF-IDF Vectorization
Train-Test Split
Model Training (Naive Bayes)
Accuracy Evaluation
Custom Message Prediction
Visualization: Ham vs Spam message count
🔍 Sample Output
Accuracy: 0.9749
predict_message("Free prize awaits! Text WIN to 12345")
# Output: Spam

predict_message("Hey, are we still on for dinner?")
# Output: Ham
📊 Visualization

A simple bar chart shows message distribution between ham and spam.

📦 How to Run
Download or clone this repository
Open the Jupyter Notebook
Make sure SMSSpamCollection.tsv is in the same folder
Run the notebook step-by-step
Try predicting your own messages!
💡 Future Ideas
Use more models (SVM, Logistic Regression)
Add more NLP cleaning (stopwords, stemming)
Try cross-validation and evaluation metrics
Export the model for web or app use
