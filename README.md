# SMS-Spam-Classifier Using NLP
SMS Spam Classifier using Natural Language Processing (NLP) and Multinomial Naive Bayes. Performs text preprocessing, Bag of Words vectorization, spam prediction, and model evaluation using Accuracy Score and Confusion Matrix.

## 🚀 Features

- SMS text preprocessing using NLP
- Removes special characters and stopwords
- Applies Porter Stemming
- Converts text into Bag of Words (BoW)
- Trains a Multinomial Naive Bayes model
- Predicts Spam or Ham messages
- Evaluates model performance using Accuracy Score and Confusion Matrix

## 🛠️ Technologies Used

- Python
- Pandas
- NLTK
- Scikit-learn
- NumPy
- Matplotlib
- Seaborn

## 📂 Project Workflow

1. Load the SMS Spam Collection dataset.
2. Clean and preprocess text data.
3. Convert text into numerical features using Bag of Words.
4. Split the dataset into training and testing sets.
5. Train a Multinomial Naive Bayes classifier.
6. Predict message labels and evaluate the model.

## ▶️ How to Run

1. Clone this repository.
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Python script:
   ```bash
   python spam_classifier.py
   ```

## 📊 Output

- Spam/Ham Prediction
- Accuracy Score
- Confusion Matrix

## 📚 Dataset

The project uses the **SMS Spam Collection Dataset**, which contains labeled SMS messages categorized as **Spam** or **Ham**.

