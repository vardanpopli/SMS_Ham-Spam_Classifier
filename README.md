# SMS_Ham-Spam_Classifier

This repository contains detailed methodology and code for a machine learning model designed to classify SMS messages as either spam or not spam (ham). The main model utilized in this project is Naïve Bayes, with other machine learning models also experimented with and documented in the 'main' file within the repository. 

Few Data Preprocessing steps has been done in this project-- can be seen within 'main', folowed by EDA which includes Bargraphs, Pichart, Histograms, Heatmaps, Wordcloud.

The model is evaluated based on the precision (Since, the data has greater Non-Spam target than spam target)

# Dataset
The dataset used in this model is taken from the kaggle ('https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset?resource=download'). It is also documented in csv format.

# Model 
This documentation the Trained model.pkl on on the given dataset usin Multinomial Naive Bayes

# Vectorizer 
This documentation contains the trained tfidf vectorizer.pkl, which can be used to vectorize the input sentence/SMS.

# Deployment_LocalNet
This notebook contain the code to deploy the model on the Local Host

# Implimentation:
1. Download the Dataset on your Desktop
2. copy the main file to your desired IDE (Or just downlaod the trained model and trained vectorizer)
3. Run the Deployment code
