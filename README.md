#### VADER_Sentiment_Analysis
*Performing Sentiment Analysis using the VADER (Valence Aware Dictionary and sEntiment Reasoner) lexicon from the NLTK library*

*VADER (Valence Aware Dictionary for Sentiment Reasoning) is a specialized model created for analyzing the sentiment of text. It considers both the polarity (positive or negative) and intensity (strength) of emotions expressed within the text. VADER is a component of the NLTK (Natural Language Toolkit) package and is widely employed for sentiment analysis purposes.*

*VADER sentiment analysis relies on a predefined dictionary that associates words with sentiment scores, which indicate the level of positive or negative sentiment associated with each word. By assessing the sentiment scores of individual words and considering their context, VADER can determine the overall sentiment conveyed by a text.*

*For example, words such as "love," "enjoy," "happy," and "like" typically indicate a positive sentiment, while words like "hate," "dislike," and "sad" convey a negative sentiment. VADER is also capable of understanding negation and modifiers, enabling it to interpret phrases like "did not love" as expressing a negative sentiment.*

*It is important to note that VADER does not aim to classify text as objective or subjective, or to determine whether a statement is a factual claim or an opinion. Its primary objective is to identify and classify the sentiment expressed in a text as positive, negative, or neutral.*

*By utilizing VADER in sentiment analysis, we can gain valuable insights into the sentiment expressed in textual data, helping us comprehend the overall emotional tone and opinion conveyed by the text.*

> *Sentiment Analysis of Newspaper Headlines and Descriptions*

* *In this project, I conducted sentiment analysis on three different data frames containing time, headlines, and descriptions from various newspapers (CNBC, the Guardian, and Reuters Headlines) . The project workflow involved loading the data, handling duplicates and missing values, and performing **sentiment analysis using the VADER** (Valence Aware Dictionary and sEentiment Reasoner) lexicon from the NLTK library.*

* *I started by merging the description and headline columns into a single text column and predicted the sentiments of the combined dataset. Utilizing algorithms such as **Linear SVC, Logistic Regression, Naive Bayes (Multinomial and Bernoulli), and CatBoost**, I aimed to accurately classify the sentiments as positive, negative, or neutral. After evaluating the performance of these algorithms, Linear SVC stood out with an impressive accuracy of almost 90%.*

* *Furthermore, I proceeded to analyze the sentiments individually based on the headlines and descriptions separately. This approach allowed me to gain insights into the sentiment composition of each aspect*

* *Overall, The project's findings highlight the significance of considering both the headlines and descriptions when predicting sentiments in financial news. This comprehensive approach using machine learning algorithms can aid in extracting valuable insights from textual data and assist in decision-making processes.*
