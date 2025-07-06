# Spam-Email-Classifier-using-Machine-Learning

Nowadays, email and SMS scams are common and can lead to loss of money or sensitive information. To reduce such risks, automatic spam detection helps filter out unwanted messages.

In this project, I used:
- Data cleaning
- TF-IDF Vectorization (to convert text to numbers)
- Logistic Regression (as the classification algorithm)


# Dataset

Dataset used: [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

It contains labeled SMS messages marked as spam or ham.


# Technologies / Libraries

- Python
- pandas
- numpy
- scikit-learn


# How to Run (Google Colab)

I did this project using Google Colab.
If you are new to Colab, follow these simple steps:

1. Upload the notebook
   - Download my `Email_classifier.ipynb` file.
   - Open [Google Colab](https://colab.research.google.com/) in your browser.
   - Click `File > Upload Notebook` and select the file.

2. Run the notebook
   - Run the cells one by one. The notebook will:
     - Load the dataset
     - Clean the text data
     - Vectorize the text using TF-IDF
     - Train a Logistic Regression model
     - Show accuracy and a classification report

3. Check results
   - At the end, you will see the accuracy (around 97%) and how well the model predicts spam messages.
