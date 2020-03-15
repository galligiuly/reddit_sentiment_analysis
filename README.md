# Political Subreddits - sentiment analysis

#### Project purpose

Train an NLP model to analyze the sentiment analysis of the of citizens on world politics.



## Data

The following [link](https://bigquery.cloud.google.com/dataset/fh-bigquery:reddit_comments?pli=1) refers to a collection of 1.7 billion comments uploaded to BigQuery and from where I started to analyze and query the data used for my work.

#### reddit_comments

The table of comments gives me a huge amount of text that helps me with my purpose. 

Analyzing `number of comments` and `number of unique authors` that write comments has been a base of a fist analysis confirming the validity of these subreddits to train my model.

#### reddit_posts

Apart from the analysis of comments I decided to make an analysis for posts because the original post (title and corpus of it) should contain more key words that better identify the subreddit, precious information for my study.

#### Objective

I'll train my model based on the information got from the following subreddits:

* politics

*  worldpolitics

* neoliberal

*  Libertarian

* Anarchism

*  socialism

*  Conservative

*  hillaryclinton

* AskTrumpSupporters

*  PoliticalHumor

*  NeutralPolitics

* PoliticalDiscussion

* ukpolitics

*  LateStageCapitalism

* geopolitics



## Project organization

| Folder          | Description                                 |
| --------------- | ------------------------------------------- |
| 01_inspection   | Analyze the data of the subreddits selected |
| 02_cleaning     | Data clieaning and pre-processing           |
| 03_filnal_model | LSTM final model implementation             |



#Tools used

*  BigQuery

- Colab
- Jupyter notebook



# Programming lenguages used

- Python
- BigQuery SQL



# Libraries

`pandas`

`numpy`

`nltk`

`sklearn`

`gensim`

`matplotlib`

`altair`

`spacy`

`keras`

`tensorflow`

`seaborn`



# Steps to exectute the job

WIP





# References

[My Linkedin](https://www.linkedin.com/in/giulia-galli-7669ba85/?locale=en_US)

