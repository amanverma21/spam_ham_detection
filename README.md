# spam_ham_detection

# Description
In the web app user can enter any message and it will return whether the input message is spam or ham.

# Dependencies must be install
To run the project, you need to install the necessary dependencies listed here:
numpy 
pandas,
flask, 
pickle

# Once the dependencies are installed, you can start the Flask application by running:
python app.py

This will start the Flask application on http://localhost:5000/.


# Usage
Once the Flask application is running, you can access the home page by visiting http://localhost:5000/. Here, you can upload a CSV file containing years of experience data and get predictions for the corresponding salaries.

# Model
The machine learning model used in this project is a Naive Bayes Classifier model that predicts whether the message is spam or ham. The model is trained on the Spam.csv dataset, which contains messages tagged as spam/ham.

The model is saved as a pickle file NB_spam_model.pkl and loaded into memory when the Flask application starts.

# Github Link:
https://github.com/amanverma21/spam_ham_detection
