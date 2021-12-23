# sentimentAnalysis

This project uses Tweets scraped from the Twitter API to answer the question: 

"How do students view online classes?"

The Tweets are cleaned and transformed into a Document Frequency Matrix using the Quanteda package. 

I then use a bag of words approach for finding positive or negative sentiment in the mined Tweets. The Hu and Liu Lexicon is used for sentiment detection.

Finally, I use a sepctral stuctural topic model to graph the topic models of the tweets and store the results of words over topics. 

My analysis concludes that the sentiment towards online class is slightly positive. 
