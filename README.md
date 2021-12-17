# Data Structures and Algorithms Final Project
Final Project for the Data Structures and Algorithms course at Hertie. 

## Preaching the Gospel 
### Do politicians tweet what is written in their party programme?

* Carlo Greß 
* Lukas Warode  
* Johannes Halkenhaeusser


# Project Summary

In this project, we are examining whether the tweets of German Members of Parliament (MP) are tweeting accordingly to their respective party's programme. More specifically, we are transforming the content of both the party programmes and the tweets into numeric vectors and calculating their cosine similarity. For this purpose, we are using the ``tweepy`` library that allows us to store the tweets of German MPs. For reasons of simplicity, we are only considering the Green MP **Annalena Baerbock** to illustrate the functionality of our code.   


## Order of files to run

In order to run our analysis, please run the following notebooks in this order: 

1. 01_data_preprocessing (Prepare twitter data)
2. 02_party_programmes  (Prepare party programme data)
3. 03_tweepy_test_setup (Prepare twitter data)
4. 04_analysis (Final analysis, matching programme and tweet contents)


## Where to download the language models:

- https://fasttext.cc/docs/en/pretrained-vectors.html
- https://fasttext.cc/docs/en/crawl-vectors.html


# Agenda
* Wir muessen vor jedem code chuck im Markdown documenten (sagt Hannah).
    * nicht zu viele sachen printen und inline comments sind nur fuer uns. 
* Which politician(s) do we want?
--> person with most followers. 
--> Annalena Baerbock 
* which similarity measure should we use?
--> Johannes sucht sich ein oder zwei aus.  
* What's the targeted code architecture?
* Who does what? (Johannes' suggestion)
    * Write an Email to Simon to discusss project generally
    * Lukas: get twitter data, save and process it, for one MP from each party?
    * Johannes: Code functions for similarity (maybe not all of them haha)
        - zusammengehoerende Woerter
        - remove stopwords
        - lemmatize
        - remove stopwords again
        - find similarity metrics
    * Carlo: Documentation and explanation of the similarity measures
        - was kann man wie plotten (an tweets und an similarity metrics.)


TO-DO DOC
https://docs.google.com/document/d/1YSW1LRMeawh-gb4fRbuEbdgbr9xOKrc9v789Zp7U8uk/edit 
