# Codsoft_ML_03
TASK 3 ( SPAM SMS DETECTION)

This project focuses on building an AI model that can classify SMS messages as either spam or legitimate (ham). The goal is to detect unwanted or malicious messages (spam) and separate them from regular (ham) communications.

Project Workflow:
1. Data Preprocessing:
Text data from SMS messages is transformed using TF-IDF (Term Frequency-Inverse Document Frequency) to convert the text into numerical features suitable for classification.

2. Model Selection:
A Support Vector Classifier (SVC) was chosen for the classification task due to its robust performance in high-dimensional spaces like text data.

3. Training:
The SVC model is trained on a labeled dataset containing SMS messages with their corresponding labels: spam or ham (legitimate).

4. Prediction:
The model can classify any new message as either spam or ham by entering the message text. This feature allows real-time message classification.

5. Output:
The output for a given message is either "spam" or "ham," indicating the likelihood of the message being malicious or legitimate.

Technologies Used:

Python: For data preprocessing and model development.
Support Vector Classifier (SVC): For SMS message classification.
TF-IDF: For converting text data into numerical features.
Scikit-learn: For implementing the machine learning model
