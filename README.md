Spam Email Detecton

This is a mini Python project created by Vishakha Singh and Vidushi Jain.
This project aims to create a simple web application for detecting spam emails using a Naive Bayes classifier. The application is built using Streamlit, a Python library for building interactive web applications.

How it Works:

Data: The application uses a predefined dataset consisting of example emails labeled as spam (1) or not spam (0).

Model Training: The dataset is used to train a Naive Bayes classifier. The text data is first transformed into numerical features using CountVectorizer, which converts the text into a matrix of token counts. Then, a Multinomial Naive Bayes model is trained on these features.

Prediction: Users can paste an email into a text area provided by the application. Upon clicking the "Predict" button, the model predicts whether the input email is spam or not.

UI: The web application interface is designed using Streamlit. It includes a text input area for the user to input the email and a button to trigger the prediction. The prediction result (spam or not spam) is displayed to the user.

Project Description:

This project demonstrates the implementation of a basic email spam detection system using machine learning techniques. It provides a user-friendly interface for users to quickly check whether an email they receive is likely to be spam. The application can be further enhanced by integrating more sophisticated models, improving the user interface, and deploying it on a web server for wider accessibility.
