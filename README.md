# British-Airways-web-scraping-task
#Extraction
After reviewing the BA flight reviews on skytrax webpage, I have decided to extract the following data elements from the reviews;Names, Reviews, hence 3442 Names and Reviews were extracted.I Retrieved the HTML data and Extracted the Data Elements, using the ScraperAPI proxy manager to block off anti-bot. 

#Data preprocessing/Transformation

Convert dictionary to pandas dataframe
Missing Value Summary
Text Data cleaning(Removing special characters, Expand Contractions, lowercase the reviews, Removing Punctuation, stopwords removal, lemmatization)

#Loading
load dataframe to csv file, with 2 columns and 3442 rows.

#EDA
The following analysis were performed to convey insigts from the extrated data 

#1. wordclouds

wordclouds was generated to see the most frequently used words in the reviews text;flight,ba,british airways,time,good, seat, service, passenger, service,staff, business class, cabin crew, food, airport, great, nice, excellent. Quick insight, passengers shared their experience with food served on the plane, aircraft seats,business class, breakfast lounge and services received from the  cabin crew and airportstaffs

#2. Sentiment analysis of text

Sentiment analysis is the analysis of how much a piece of text is positive and opinionated checking the polarity, i.e., how much a text is positive or negative

#Top 3 Random Reviews with highest Polarity Reviews
Review 1 was grateful for excellent premium host service and time management
 
Review 2 was apprecaited of the good seat

Review 3, was apprcaitive of the great service from the cabin crew, exellent service.

#Top 3 Random Review with lowest Polarity
Review 1 complained about luggage allowance, horrible flight.

Review 2 compalined about the food i.e chicken wrap being horible, inedible , disguating sausage and inedible hash brown, advised potential passengers to go have traditional breakfast, rubbish ba.

Review 3. complained about the croissant cream cheese onion breakfast fruit bar, wrap cellophane, couldnt eat it bust wasted it.

#3. Topic Modelling.
Topic Modelling are a type of statistical language models used for uncovering hidden structure in a collection of texts 

#Latent Dirichlet Allocation (LDA) Analysis
 Is a generative probabilistic model that assumes each topic is a mixture over an underlying set of words, and each document is a mixture of over a set of topic probabilities

#tokenizing the text and removing stopwords
#LDA model training
#Dominant topic and its percentage contribution in each document
Topic 1.0
Topic % Contribution = 0.975
Most dominant keywords : seat, flight, food, good, crew, 1hr, cabin, service, time, ba
