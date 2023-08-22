# Sentimental_Analysis
To check the sentiment of twitter data using machine learning model
Twitter Data Sentimental Analysis Using Machine Learning Multiple classification
Sentiment Analysis is the process of determining the conceptions, judgments, feelings, opinions, viewpoints, conclusions, and other notions towards anything. It is a technique to analyze texts, images, emojis and various other actions to know what other people think about a product, service, company, brand name, or a reaction to a specific event, social movement, etc
Sentiment analysis is the process of automatically classifying text data according to their polarity, such as positive, negative, or neutral.[1]
In the context of Twitter data, sentiment analysis is used to analyze the sentiments expressed in tweets and understand how users are talking about products, services, or various topics[1]
One approach to sentiment analysis is using multiple classifications. This involves classifying the extracted data into sentiment polarities, such as positive, neutral, and negative classes[3]
By using multiple classifications, more granular insights can be obtained, such as identifying specific themes or topics associated with each sentiment
The goal of sentiment analysis on Twitter data using multiple classification is to gain insights into customer opinions, drive business decisions, and identify potential issues or crises early on
Data Set and related Libraries
   A data set was downloaded from Kaggle.com  and analysis was performed on it .
   Some of the key libraries used are :-
•	Panda , Seaborn and Numpy 
 For Data  manipulation , analysis and working. Panda offers different types of Data Structure while Numpy helps in working with arrays and seaborn is used for visualization and exploratory data analysis.
 
•	Metplotlib.pyplot  
For working with 2D graphics. It helps to generate a 2D graph between 2 given coordinates of data itself and helps in plotting of figures , interpolation and so on.

•	Regular Expression and String 
We are familiar with the term Regex or Regular Expressions. It helps to check string validation to pre process data to extract the main content to work upon. 

•	NLTK 
It is the main link of NLP in our project. It stands for natural language toolkit and is used to perform on unstructed data and human-readable types.
 
•	Warnings 
It is to handle any exceptions or warn of any situations that aren’t necessary exceptions .This ensures proper functioning of the code .
TOKENIZATION 
 Reduction of words into individual tokens/words to perform operations.
 

2.	 PROCESSING – (a) 
Removing special characters , popular parts of speech and reduce the set to words that contribute to analysis.
 

3.	PROCESSING – (b)
With the remaining words , we need to classify them as positive , negative or neutral to perform analysis.


 

