# **Twitter Sentiment Analysis**

This project performs sentiment analysis on Twitter data using machine learning techniques.

# **Overview**
Twitter sentiment analysis is a task of analyzing tweets and categorizing them into positive or negative sentiment. In this project, we utilize a machine learning model to automate this process.

# **Dataset**
The dataset used in this project is the Twitter Sentiment dataset available on Kaggle. It contains 1.6 million tweets labeled with sentiments (positive or negative)
link : https://www.kaggle.com/datasets/kazanova/sentiment140

# **Work Done**
We started by setting up the environment , installing the dependencies and download the data from kaggle. Then we moved to the Data preprocessing,  by renaming columns, handling missing values, converting the target labels, and performing stemming on the textual data to reduce words to their root forms.

Then we moved to Feature engineeering part,  It separates the text data (X) from the target labels (y) and splits the dataset into training and testing sets using a stratified split to maintain class distribution. In order to prepare the Data to be processed by our model we need to convert our text column conatining alphabetic composants to numeric ones so uses TF-IDF vectorization to convert textual data into numerical features for training the model.

After this, we pass to the training model part where we train the model and test it then finally saving the model.



# **Future Work**
  - Experiment with different machine learning algorithms and techniques to improve model performance.
  - Explore additional features or data sources.
